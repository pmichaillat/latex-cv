# Minimalist LaTeX Template for Academic CVs

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic CV. The template carefully follows typographical best practices and has a minimalist design.  It is particularly well suited for researchers, professors, and other academics. The design emphasizes clarity, structure, and visual simplicity. 

## Illustration

+ A CV produced by the template can be viewed at https://pascalmichaillat.org/cv.pdf.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `cv.tex` to replace the boilerplate content with the content of your CV. 
+ Compile `cv.tex` with pdfTeX. This will generate a PDF file of your CV named `cv.pdf`.
+ The LaTeX style file `cv.sty` collects all the commands to format the CV. The file must be included in the same folder as `cv.tex`. It can be modified to alter the CV's format.
+ The `cv.pdf` file is not required: it only illustrate the output of the template. It will be overridden once `cv.tex` is compiled.
+ Note: The template is not very user-friendly at the moment. I plan to improve usability when time permits. 

## Software

The template was developed, tested, and validated on a Mac with the MacTeX-2023 distribution. 

While the template should also work on other operating systems and with other LaTeX distributions, compatibility cannot be guaranteed. Users on Windows or Linux systems, or those using different LaTeX distributions, may need to make minor adjustments. [Please report](https://github.com/pmichaillat/latex-cv/issues) any compatibility issues or bugs to help improve cross-platform support.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Related resources

+ [hugo-website](https://github.com/pmichaillat/hugo-website) - This Hugo template produces a minimalist academic website that can host your academic CV.
