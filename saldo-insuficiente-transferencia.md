# TC-003 - Validación de mensaje de error por saldo insuficiente en transferencia

## Objetivo:
Validar el mensaje que muestra el sistema cuando el usuario intenta realizar una 
transferencia por un monto mayor al saldo disponible en la cuenta origen.

## Precondiciones:
- El usuario ha iniciado sesión en https://bancoficticio.demo
- El usuario se encuentra en la página principal donde puede ver sus cuentas y saldos.
- La cuenta de origen tiene un saldo menor al que el usuario desea transferir.
- Existe una cuenta de destino disponible para recibir la transferencia.

## Pasos:
1. Hacer clic en el botón "Transferencias" desde la página principal.
2. Seleccionar la cuenta de origen.
3. Localizar el campo "Monto".
4. Ingresar un monto mayor al saldo disponible de la cuenta de origen.
5. Seleccionar la cuenta de destino.
6. Hacer clic en el botón "Transferir" o "Continuar".
7. Observar el mensaje que muestra el sistema respecto a la operación.

## Resultado esperado:
El sistema debe mostrar un mensaje de error indicando que el usuario no cuenta
con el saldo suficiente en su cuenta para realizar la transferencia.

## Resultado real:
(No ejecutado)
