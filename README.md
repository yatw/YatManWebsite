
This website is a quick and easy way to get to know me. It is currently hosted on [Netlify](https://www.netlify.com/).

Feel free to come visit me at www.wongyatman.cf

**To Generate the resume as pdf**

Use [wkhtmltopdf](https://wkhtmltopdf.org/) ,open command prompt inside the same folder as wkhtmltopdf.exe, run
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 sorce destination
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 file:///C:/Users/Wong/Desktop/MyWebsite/resume2019.html C:/Users/Wong/Desktop/wong2019.pdf
```

**To Generate Mock resume as pdf**
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 file:///C:/Users/Wong/Desktop/MyWebsite/mockResume2019.html C:/Users/Wong/Desktop/mock2019.pdf
```

**To Generate coverLetter as pdf**
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 file:///C:/Users/Wong/Desktop/MyWebsite/coverLetter.html C:/Users/Wong/Desktop/coverLetter.pdf
```