# Router

##Usage

Include this class to index.php in your project.

Create new instance with this class and with array $routes: key => route, value => include file

```
$routes = [
'/' => '../homepage.php',
'/create-user' => '../create_user.php',
...
];
$route = new Route($routes);
$route->get();
```