
This website is a quick and easy way to get to know me. It is currently hosted on [Netlify](https://www.netlify.com/).

Feel free to come visit me at www.wongyatman.cf

**To Generate the resume as pdf**


Use [wkhtmltopdf](https://wkhtmltopdf.org/) , run in command prompt
```
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 sorce destination
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 file:///C:/Users/Wong/Desktop/MyWebsite/resume_2019.html C:/Users/Wong/Desktop/wong_2019.pdf
wkhtmltopdf --page-size Letter --disable-smart-shrinking --margin-top 5 --margin-bottom 5 file:///C:/Users/Wong/Desktop/MyWebsite/mock_resume_2019.html C:/Users/Wong/Desktop/mock_2019.pdf
```