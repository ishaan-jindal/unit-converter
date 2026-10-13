# Unit Converter

A single-file, dependency-free unit converter that runs in the browser.

## Supported units

| Category    | Units                              |
|-------------|------------------------------------|
| Length      | m, km, cm, mm, mi, yd, ft, in      |
| Mass        | kg, g, mg, lb, oz                  |
| Temperature | C, F, K                            |

Results update as you type, and the ⇆ button swaps the from/to units.

## Usage

Open `index.html` in a browser. No build step or server needed.

## Tests

Conversion checks run as `console.assert` calls on page load; any failure shows up in the browser console.
