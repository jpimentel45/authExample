# CORE CONCEPTS: MIDDLEWARE

## kernel.php: component to laravel

Analogy: middleware layers of the onion
each middleware represents a layer
each layer do a number of checks: authorize, redirect, anything you want

Middleware is our global middleware meaning it will pass through each in order to load

routemiddleware should only be required in routes that require authentication, verified, signed up, or etc
