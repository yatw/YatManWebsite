## To Generate the resume as pdf

Use [wkhtmltopdf](https://wkhtmltopdf.org/), open command prompt inside the same folder as wkhtmltopdf.exe, run

  
**wkhtmltopdf format**
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 sorce destination
```

**To Generate resume as pdf**
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 D:\CodingFiles\SideProjects\MyWebsite/resume2019.html C:/Users/Wong/Desktop/wong2019.pdf
```
  

**To Generate coverLetter as pdf**
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 D:\CodingFiles\SideProjects\MyWebsite/coverLetter.html C:/Users/Wong/Desktop/coverLetter.pdf
```