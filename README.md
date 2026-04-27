# Minimalist LaTeX Template for Academic CVs

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic CV. The template carefully follows typographical best practices and has a minimalist design. It is particularly well suited for researchers, professors, and other academics. The design emphasizes clarity, structure, and visual simplicity. The repository also contains a variant of the template to create a compact, one-page CV.

## Documentation

The template and its variant are documented at https://pascalmichaillat.org/f/.

## Illustration

The CV produced by the template can be viewed at https://pascalmichaillat.org/f.pdf. The one-page CV can be viewed at https://pascalmichaillat.org/fo.pdf.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `cv.tex` to replace the boilerplate content with the content of your CV. 
+ Compile `cv.tex` with pdfTeX. This will generate a PDF file of your CV named `cv.pdf`.
+ The LaTeX style file `cv.sty` collects all the commands to format the CV. The file must be included in the same folder as `cv.tex`. It can be modified to alter the CV's format.
+ The `cv.pdf` file is not required: it only illustrates the output of the template. It will be overridden once `cv.tex` is compiled.

To produce a one-page CV, edit the LaTeX file `onepage.tex` instead of `cv.tex`, and follow the same steps. The commands specific to the one-page CV are in the LaTeX style file `onepage.sty` (which must be used in conjunction with `cv.sty`). 

## Software

+ The template is currently operational with TeX Live 2025 on macOS.
+ Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-cv/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Related resources

+ [hugo-website](https://github.com/pmichaillat/hugo-website) - This Hugo template produces a minimalist academic website that can host your academic CV.