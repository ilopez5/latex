# Invoice LaTeX Template

## Basic Usage
1. Modify the Payer/Payee lines in `invoice.tex`.
2. Add `\hourrow{...}{...}{...}` rows for dates you worked.
3. Compile with pdfLaTeX or whatever alternative.

## Suggestion
You can programmatically do this by adding a single line
```latex
\input{file.tex}
```
and have some program write to that file. I have made a similar
script using Python and the Zipbooks API (requires you to use
Zipbooks when logging your hours however).

## Credit
Original source [here](https://www.latextemplates.com/template/invoice)
I simply made some modifications to it.
