# Proyecto practico 1

- Comprender la integración de funciones personalizadas y módulos externos para resolver problemas complejos.
- Implementar técnicas de programación orientada a objetos (POO) para mejorar la estructura y mantenibilidad del código.

En esta lección, se profundizará en el uso avanzado de Python, enfocándose en la creación de un proyecto práctico que combine funciones personalizadas, módulos externos y patrones de diseño orientados a objetos. El objetivo es aplicar estos conceptos para desarrollar una aplicación que simule un sistema bancario básico, incluyendo operaciones como depósitos, retiros y transferencias entre cuentas.

El proyecto consistirá en crear una clase `CuentaBancaria` con métodos para realizar transacciones y gestionar saldos. Además, se utilizarán módulos externos como `datetime` para registrar fechas de las transacciones y `random` para simular movimientos aleatorios en cuentas test. Los estudiantes deberán implementar la lógica necesaria para manejar múltiples cuentas y realizar operaciones simultáneamente.

### Ejercicio
Implementa una clase `CuentaBancaria` que tenga los siguientes métodos:
- `__init__(self, titular, saldo_inicial)`: Inicializa el objeto con un titular y un saldo inicial.
- `depositar(self, monto)`: Añade `monto` al saldo de la cuenta.
- `retirar(self, monto)`: Resta `monto` del saldo de la cuenta, si es posible (no se puede retirar más dinero que el disponible).
- `transaccion(self, otra_cuenta, monto)`: Realiza una transferencia de `monto` desde esta cuenta a `otra_cuenta`.

Utiliza el módulo `datetime` para registrar la fecha y hora de cada transacción. Prueba tu implementación creando varias cuentas y realizando diversas operaciones.

### Resumen
- Integración efectiva de funciones personalizadas y módulos externos.
- Uso de programación orientada a objetos para estructurar el código de manera más eficiente y mantenible.