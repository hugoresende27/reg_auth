- https://medium.com/@ghaith.gtari/a-detailed-guide-on-implementing-registration-and-authentication-in-symfony7-part1-143b6e5cd446

1. composer `require maker orm validator security twig`, this will add :
    - orm: This bundle allows us to use an ORM (Symfony defaults to Doctrine).
    - validator: This bundle is used for input validation.
    - maker: This package (referred to as a bundle in Symfony) is used for code generation.
    - security: This bundle is responsible for all security aspects of our application and will be used for the authentication process.
    - Twig: Twig is the default templating engine for Symfony.

2. php `bin/console make:user` && `php bin/console make:migration` && `php bin/console doctrine:migration:migrate`

3. https://symfony.com/doc/current/security.html#form-login `php bin/console make:security:form-login`

4. `php bin/console make:registration` for registration form and routes