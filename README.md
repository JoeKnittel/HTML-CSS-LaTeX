# HTML-CSS-LaTeX
## Web-Ready Actuarial Notes Typeset in LaTeX and Stylized with CSS (2020)

*This project was completed in my spare time as a way to facilitate my actuarial studies.*

Studying for actuarial exams requires one to ingest massive amounts of often-equation-dense information. The nature of the task necessitates an orderly approach, and I quickly learned that, with my chicken scratch, hundreds of pages of hand-written notes wouldn't suffice.

Therefore, **I devised a way to produce beautiful, stylized notes that would help me prepare for actuarial exams.** The process went as follows:

1) Compose notes as [.rmd](https://rmarkdown.rstudio.com/) files, embedding LaTeX equations wherever necessary
2) Include CSS styles directly within the files 
3) [Knit](https://en.wikipedia.org/wiki/Knitr#:~:text=knitr%20is%20an%20engine%20for,%2C%20AsciiDoc%2C%20and%20reStructuredText%20documents.) the files to HTML
4) Review notes in any web browser, taking advantage of [MathJax](https://www.mathjax.org)'s equation rendering

Below is an example of my notes from the Loss Models section of Exam STAM, in all their stylized, web-ready glory:

<img src = "https://github.com/JosephKnittel/HTML-CSS-LaTeX/blob/main/Images/notes_demo.gif?raw=true" width = 70%>

<hr>

### Contained in this repository:
- Sample collection of notes (Exam STAM)
  - .rmd files used to generate the stylized notes
  - .html output files
