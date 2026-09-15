# Investigación #1 - Seguridad en C# y Windows Forms

Este repositorio contiene los programas desarrollados para la investigación sobre **Principios de Seguridad en C# y Validaciones**, correspondiente a la materia **Herramientas de la Programación Aplicada III (.NET)**.

El objetivo de los ejemplos es demostrar de forma práctica algunas buenas prácticas de seguridad aplicadas en aplicaciones de escritorio desarrolladas con **C# y Windows Forms**.

## Escenarios desarrollados

### 1. Manejo seguro de contraseñas
Programa de registro de usuarios que utiliza **BCrypt** para generar un hash de la contraseña y evitar almacenarla directamente en texto plano.

Incluye:
- Validación de campos
- Confirmación de contraseña
- Uso de `ErrorProvider`
- Uso de `PasswordChar`
- Generación de hash con BCrypt

### 2. Prevención de SQL Injection
Programa que demuestra la diferencia entre una consulta SQL construida de forma insegura mediante concatenación y una consulta segura utilizando parámetros.

Incluye:
- Ejemplo de entrada maliciosa
- Consulta vulnerable
- Consulta parametrizada
- Explicación visual de la diferencia entre ambas

### 3. Validación y control de acceso
Programa que demuestra validación de entradas y control de permisos según el rol del usuario.

Incluye:
- Validación de nombre, edad y correo
- Uso de `ErrorProvider`
- Roles de Administrador y Usuario
- Control de permisos
- Aplicación del principio de mínimo privilegio

## Tecnologías utilizadas

- C#
- Windows Forms
- Visual Studio
- .NET
- BCrypt.Net-Next

## Estructura

Cada escenario fue desarrollado como un proyecto independiente para facilitar su ejecución y explicación durante la presentación.

## Objetivo académico

Los programas buscan relacionar la programación segura con atributos de calidad del software como:

- Seguridad
- Confiabilidad
- Mantenibilidad
- Usabilidad

También se relacionan con buenas prácticas de desarrollo y con el modelo de calidad de software **ISO/IEC 25010**.
