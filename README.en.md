
### Código del `README.en.md` (Inglés)
Este será el archivo en inglés, que los usuarios no hispanohablantes pueden seleccionar manualmente:

```markdown
# VAT Calculator

![VAT Calculator](https://img.shields.io/badge/VAT-Calculator-blue)  
A simple calculator to add or subtract VAT (21%) from an amount, built with HTML, CSS, and JavaScript.

## Description

This VAT calculator allows users to quickly calculate the 21% VAT on an entered amount. You can add VAT to get the total or subtract VAT to get the taxable base. It includes additional features such as copying results to the clipboard, keyboard shortcuts, and a light/dark mode.

The project is hosted on GitHub Pages and can be accessed directly via the following link:  
🔗 [VAT Calculator](https://jelgezabal.github.io/Calculadora-IVA/)

## Features

- **Add VAT**: Calculates the total amount by adding 21% VAT.
- **Subtract VAT**: Calculates the taxable base by subtracting 21% VAT.
- **Copy Results**: Copies the final result (Total or Taxable Base) to the clipboard with a button <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path></svg> or with `Ctrl + C`.
- **Keyboard Shortcuts**:
  - `Enter` or `Arrow Up (↑)`: Adds VAT.
  - `Arrow Down (↓)`: Subtracts VAT.
  - `Ctrl + C`: Copies the latest result.
- **Light/Dark Mode**: Press the light <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg> or dark <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 1 1-8 0 4 4 0 0 1 8 0z"></path></svg> icon to toggle themes.
- **Input Validation**: Only allows numbers and commas for decimals.
- **Responsive Design**: Adapted for mobile and tablet devices.
- **Language Detection**: Spanish or English based on the browser.

## Usage

1. **Access the Calculator**:
   - Visit [https://jelgezabal.github.io/Calculadora-IVA/](https://jelgezabal.github.io/Calculadora-IVA/).
   
2. **Enter an Amount**:
   - Type an amount in the text field (e.g., `100.50`). Only numbers and commas are allowed.

3. **Perform a Calculation**:
   - Click **Add VAT** (or press `Enter` or `Arrow Up`) to get the total with VAT.
   - Click **Subtract VAT** (or press `Arrow Down`) to get the taxable base without VAT.

4. **Copy the Result**:
   - Click the copy icon <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path></svg> next to the final result, or press `Ctrl + C`.

5. **Change the Theme**:
   - Press the light <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg> or dark <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 1 1-8 0 4 4 0 0 1 8 0z"></path></svg> icon to toggle between themes.

## Example

- **Add VAT**:
  - Amount: `100`
  - VAT (21%): `21.00`
  - Total: `121.00`

- **Subtract VAT**:
  - Amount with VAT: `121`
  - VAT (21%): `21.00`
  - Taxable Base: `100.00`

## Installation (for Developers)

If you want to use or modify this calculator locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jelgezabal/Calculadora-IVA.git
