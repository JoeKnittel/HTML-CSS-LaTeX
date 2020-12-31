# HTML-CSS-LaTeX
## Web-Ready Actuarial Notes Typeset in LaTeX and Stylized with CSS

*This project was completed in my spare time as a way to facilitate my actuarial studies.*

Studying for actuarial exams requires one to ingest massive amounts of often-equation-dense information. The nature of the task necessitates an orderly approach, and I quickly learned that, with my chicken scratch, hundreds of pages of hand-written notes wouldn't suffice.

Therefore, **I devised a way to produce beautiful, stylized notes that would help me prepare for actuarial exams.** The process went as follows:

1) compose notes as [.rmd](https://rmarkdown.rstudio.com/) files, embedding <img src="https://raw.githubusercontent.com/JoeKnittel/HTML-CSS-LaTeX/main/Images/latex_transparent.png" width = "4%"> equations wherever necessary
2) include CSS styles directly within the files 
3) [knit](https://en.wikipedia.org/wiki/Knitr#:~:text=knitr%20is%20an%20engine%20for,%2C%20AsciiDoc%2C%20and%20reStructuredText%20documents.) the files to HTML
4) review notes in any web browser, taking advantage of [MathJax](https://www.mathjax.org)'s equation rendering

Below is an example of my notes from the Loss Models section of Exam STAM, in all their stylized, web-ready glory:

<img src = "https://github.com/JosephKnittel/HTML-CSS-LaTeX/blob/main/Images/notes_demo.gif?raw=true" width = 70%>

<hr>

### Contained in this repository:
- sample collection of notes (exam stam)
  - .rmd files used to generate the stylized notes
  - .html output files
