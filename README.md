# Calculadora de IVA

![Calculadora de IVA](https://img.shields.io/badge/IVA-Calculadora-blue)  
Una calculadora simple para sumar o restar el IVA (21%) a un importe, creada con HTML, CSS y JavaScript.

## Descripción

Esta calculadora de IVA permite a los usuarios calcular rápidamente el IVA (21%) sobre un importe ingresado. Puedes sumar el IVA para obtener el total o restar el IVA para obtener la base imponible. Incluye funciones adicionales como copiar resultados al portapapeles, atajos de teclado, y un modo claro/oscuro.

El proyecto está alojado en GitHub Pages y puede ser accedido directamente desde el siguiente enlace:  
🔗 [Calculadora de IVA](https://jelgezabal.github.io/Calculadora-IVA/)

## Características

- **Sumar IVA**: Calcula el importe total sumando el 21% de IVA.
- **Restar IVA**: Calcula la base imponible restando el 21% de IVA.
- **Copiar resultados**: Copia el resultado final (Total o Base Imponible) al portapapeles con un botón <img src="assets/copy.svg" alt="Copiar" width="16" height="16"> o con `Ctrl + C`.
- **Atajos de teclado**:
  - `Enter` o `Flecha Arriba (↑)`: Suma el IVA.
  - `Flecha Abajo (↓)`: Resta el IVA.
  - `Ctrl + C`: Copia el resultado más reciente.
- **Modo claro/oscuro**: Alterna entre temas claro y oscuro con un botón <img src="assets/moon.svg" alt="Modo oscuro" width="24" height="24">/<img src="assets/sun.svg" alt="Modo claro" width="24" height="24">.
- **Validación de entrada**: Solo permite números y comas para decimales.
- **Diseño responsivo**: Adaptado para móviles y tablets.
- **Detección de idioma**: Español o inglés según el navegador.

## Uso

1. **Accede a la calculadora**:
   - Visita [https://jelgezabal.github.io/Calculadora-IVA/](https://jelgezabal.github.io/Calculadora-IVA/).
   
2. **Ingresa un importe**:
   - Escribe un importe en el campo de texto (ejemplo: `100,50`). Solo se permiten números y comas.

3. **Realiza un cálculo**:
   - Haz clic en **Sumar IVA** (o presiona `Enter` o `Flecha Arriba`) para obtener el total con IVA.
   - Haz clic en **Restar IVA** (o presiona `Flecha Abajo`) para obtener la base imponible sin IVA.

4. **Copia el resultado**:
   - Haz clic en el ícono de copiar <img src="assets/copy.svg" alt="Copiar" width="16" height="16"> junto al resultado final, o presiona `Ctrl + C`.

5. **Cambia el tema**:
   - Haz clic en el ícono de <img src="assets/moon.svg" alt="Modo oscuro" width="24" height="24">/<img src="assets/sun.svg" alt="Modo claro" width="24" height="24"> para alternar entre modo claro y oscuro.

## Ejemplo

- **Sumar IVA**:
  - Importe: `100`
  - IVA (21%): `21,00`
  - Total: `121,00`

- **Restar IVA**:
  - Importe con IVA: `121`
  - IVA (21%): `21,00`
  - Base imponible: `100,00`

## Instalación (para desarrolladores)

Si deseas usar o modificar esta calculadora localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jelgezabal/Calculadora-IVA.git
