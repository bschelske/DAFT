# Dimensional Analysis Format Tool (DAFT)

DAFT is a small offline tool for writing neat dimensional-analysis
(factor-label) work, the kind of setup chemistry students see as

> 10.0 g H₂ × (1 mol H₂ / 2.016 g H₂) × (2 mol H₂O / 2 mol H₂) × (18.02 g H₂O / 1 mol H₂O) = 89.4 g H₂O

Type the factors in, and DAFT draws them in either the **railroad** ("train
track") layout or as **fractions separated by ×**, with cancelled units crossed
out. You can then paste or attach the result when answering a student's email.

## Getting started

**Use it online:** https://benschelske.com/DAFT/

**Or offline:** download `index.html` (you can rename it, e.g. to `DAFT.html`) and
double-click it to open it in any modern browser. No install or internet connection is needed.

## How to use it

- **Problem / heading** (optional): text shown above the work, such as the
  question or the balanced equation.
- **Factors**: each box is one column. Type the top in the upper field and the
  bottom in the lower field. Leave the bottom empty for the starting amount.
  Use ← → to reorder factors and ✕ to remove one.
- **Answer**: shown after an "=" at the end.
- **Note** (optional): text shown below the work.
- **Style / Size / Font**: switch between railroad and fractions-with-×, and
  adjust the text.

The preview updates as you type. Your current problem is saved in the browser
automatically, so it's still there the next time you open the file.

### Typing shortcuts

| Type       | You get                    |
|------------|----------------------------|
| `H_2O`     | H₂O (subscript)            |
| `10^{23}`  | 10²³ (superscript)         |
| `Cl^-`     | Cl⁻                        |
| `~g H_2~`  | g H₂ with a cancel line    |
| `*`        | ×                          |
| `\*`       | a literal *                |

Use braces for anything longer than one character: `_{12}`, `^{2+}`.

## Sharing the work

- **Copy image**: copies the work to the clipboard so you can paste it directly
  into an email. This works in Chrome and Edge. Some browsers block it when the
  file is opened from your computer; if so, use Download PNG.
- **Download PNG**: saves a high-resolution image to attach.
- **Print / Save as PDF**: opens the print dialog with only the work on the
  page. Choose "Save as PDF" as the printer to get a PDF.

## License

Released under the [MIT License](LICENSE). You're free to use, change, and share
it, including in your own classes.

Written with help from Claude (Anthropic).
