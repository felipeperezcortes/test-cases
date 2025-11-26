# TC-001 - Validación de formato RUT en login

## Objetivo:
Validar que cuando el usuario ingrese un RUT con formato incorrecto en el login, 
el sistema muestre un mensaje de error que indique que el formato no es válido
y entregue un ejemplo de formato correcto.

## Precondiciones:
- El usuario se encuentra en la página https://bancoficticio.demo/login
- El navegador compatible está abierto. (Chrome o Safari)

## Pasos:
1. Localizar el campo "RUT o usuario" en la página de login.
2. Ingresar RUT con formato invalido (ejemplo: 12345678).
3. Ingresar una contraseña genérica en el campo "Contraseña".
4. Hacer click en el botón "Ingresar".
5. Observar el mensaje de error mostrado bajo el campo RUT.

## Resultado esperado:
- El sistema debe mostrar un mensaje de error indicando que el formato de RUT 
no es válido y debe incluir un ejemplo de formato correcto.

## Resultado real:
- (No ejecutado)
