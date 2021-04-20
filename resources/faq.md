# FAQ

## How can I convert between file types?

I generally don't recommend converting back and forth between file types \(this is time consuming and a bit annoying\), but if you're thinking of making the switch, here are some useful websites to help you convert your file:

* [Pandoc](https://pandoc.org/index.html) allows conversion between many file types! To use it, you will need to type some commands in the terminal --- luckily the website has [step-by-step instructions](https://pandoc.org/getting-started.html) to help.
* I like to use [AbiWord](https://www.abisource.com) to convert .pdf files to .tex files. To do this in the terminal you can first [change directories to the file location](https://www.wikihow.com/Change-Directories-in-Command-Prompt), then type `abiword --to=tex filename.pdf`
* There are also lots of online converters, where you can upload a file you'd like to convert. For example, [Docx2LaTeX](https://www.docx2latex.com) lets you convert Microsoft Word or Google docs to LaTeX.

## Can you really run R code in LaTeX?

Yes. It's called Sweave or knitr, and it's very handy!

If you have a [LaTeX distribution installed](../module-1/access/#installing-latex), then you can compile a LaTeX file inside RStudio using Sweave. Here are some instructions explaining how to create an RSweave file and instert R chunks: [https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr](https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr)

Alternatively, you can include your R code in an Overleaf file using knitr. To start writing R chunks in your Overleaf file, simply change the file extension from main.tex to main.Rtex, and you're ready to go. Overleaf's guide on this is great, and even includes some examples: [https://www.overleaf.com/learn/latex/Knitr](https://www.overleaf.com/learn/latex/Knitr)



