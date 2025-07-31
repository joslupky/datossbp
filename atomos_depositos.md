|   # | Columna                      | Descripción                                                                    | Formato                      |   Cantidad de caracteres |
|----:|:-----------------------------|:-------------------------------------------------------------------------------|:-----------------------------|-------------------------:|
|   1 | Fecha                        | Corresponde a la fecha del periodo mensual que está reportando la información. | AAAAMMDD                     |                        8 |
|   2 | Cod_banco                    | Código asignado por la Superintendencia de Bancos de Panamá.                   | Alfanumérico de tres dígitos |                        3 |
|   3 | Cod_Subsidiaria              | Código de la Subsidiaria del banco.                                            | Texto de cuatro caracteres   |                        4 |
|   4 | Tipo_Depósito                | Código del Tipo de Depósito (SB05).                                            | Alfanumérico de dos dígitos  |                        2 |
|   5 | Tipo_Cliente                 | Código del tipo de cliente (SB20).                                             | Alfanumérico de dos dígitos  |                        2 |
|   6 | Tasa                         | Tasa pactada por el banco.                                                     | Numérico con dos decimales   |                      nan |
|   7 | Origen                       | Clasificación del depósito (L o E).                                            | Texto de un carácter         |                        1 |
|   8 | Cod_región                   | Código del país o provincia del cuentahabiente.                                | Alfanumérico de tres dígitos |                        3 |
|   9 | Fecha_Inicio                 | Fecha de apertura de la cuenta.                                                | AAAAMMDD                     |                        8 |
|  10 | Fecha_Vencimiento            | Fecha de vencimiento del depósito.                                             | AAAAMMDD                     |                        8 |
|  11 | Monto                        | Saldo de la captación.                                                         | Numérico con dos decimales   |                      nan |
|  12 | Monto_Pignorado              | Monto pignorado.                                                               | Numérico con dos decimales   |                      nan |
|  13 | Numero_renovación            | Veces que ha sido renovado.                                                    | Numérico                     |                      nan |
|  14 | Fecha_Renovación             | Fecha de renovación del depósito.                                              | AAAAMMDD                     |                        8 |
|  15 | Intereses_por_Pagar          | Intereses acumulados por pagar.                                                | Numérico con dos decimales   |                      nan |
|  16 | Periodicidad_pago_intereses  | Periodicidad de pagos (SB26).                                                  | Texto de dos dígitos         |                        2 |
|  17 | Identificación_cliente       | Identificación del cliente.                                                    | Texto de 50 caracteres       |                       50 |
|  18 | Identificación_Cuenta        | Identificación de la cuenta.                                                   | Texto de 50 caracteres       |                       50 |
|  19 | Actividad                    | Actividad principal del cliente (SB109).                                       | Texto de 19 caracteres       |                       19 |
|  20 | Tamaño_Empresa               | Tamaño de la empresa (SB67).                                                   | Texto de 2 caracteres        |                        2 |
|  21 | Género                       | Género del cuentahabiente (SB82).                                              | Texto de 2 caracteres        |                        2 |
|  22 | Beneficiario_declarado       | Depósito mantiene beneficiarios.                                               | Texto de 2 caracteres        |                        2 |
|  23 | Estatus_actividad_movimiento | Movimiento operativo del depósito.                                             | Texto de 2 caracteres        |                        2 |