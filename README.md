# Algorithms for Massive Datasets

This repository contains a LaTeX file that generates a PDF document comprising comprehensive notes for the course "Algorithms for Massive Datasets" taught by [Dario Malchiodi](https://malchiodi.di.unimi.it/teaching/AMD/2022-23/it) based on the content from the book [Mining of Massive Datasets](http://www.mmds.org/). The PDF document serves as a reference guide and study material for the course. However, please note that we do not assume any responsibility for the correctness of the notes provided.

# How to compile 

Add the files in `./style` folder to your `TEXMFHOME/tex/latex` (how to know TEXMFHOME: `kpsewhich -var-value TEXMFHOME`).
And run `sudo texhash` or `sudo mktexlsr` or `sudo texconfig`, in the last case you should choose `REHASH` option and then `exit`. 

**Compile**

`latexmk --shell-escape ./algorithms-for-massive-datasets.tex` 

or

`pdflatex --shell-escape ./algorithms-for-massive-datasets.tex` 

# Contributing
If you notice any errors, typos, or have suggestions for improving the notes, we welcome your contributions. You can open an issue or submit a pull request with your proposed changes. Together, we can enhance the quality and usefulness of this resource for future learners.

# Note
Please be aware that these notes are meant to be a supplementary resource and should not be considered as definitive answers or solutions. They are based on content from the book and are not a substitute for the course lectures or assigned readings. Make sure to consult the course materials and engage in discussions with your instructor or peers to deepen your understanding of the course topics.

We wish you the best of luck with your exam preparation! However, please remember that using this resource does not guarantee specific outcomes or results on the exam.

## License

This repository is licensed under the [GNU General Public License (GPL)](https://www.gnu.org/licenses/gpl-3.0.html). Please review the license file provided in the repository for more information regarding the terms and conditions of the GPL license.

## Contact

If you have any questions or suggestions regarding this repository, please don't hesitate to reach out. You can contact us via the GitHub repository or through the following channels:
- Email: [federico.bruzzone.i@gmail.com] or [federico.bruzzone@studenti.unimi.it]

We hope you find this repository helpful in preparing for your "Algorithms for Massive Datasets" exam. Good luck!
