# TallerJWT
Taller JWT - pre configurado

## Usuarios
```
Admin - admin:admin
User - user:password
Disabled - disabled:password (this user is disabled)
```

## Body para el endpoint POST **/auth**
```
{
    "username": "admin",
    "password": "admin"
}
```

## Token envio de informacion - Header
```
Authorization: eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJ1c2VyIiwiYXVkaWVuY2UiOiJ3ZWIiLCJjcmVhdGVkIjoxNDg0OTE4NjA2ODMwLCJleHAiOjE0ODU1MjM0MDZ9.ghLIqZM0wgWmL_a6_OGYjuwtaDUDbQaBFGndkfy2DNwDgu05vuoW_d6aS9iCNsi6Ajxjr8rOEYlV7QFALA9seQ
```
