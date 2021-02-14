# SpaceXData
 
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.1.
 
This project was initiated as a test to check the codeing level along with few other thing to get hired...
 
Some of the things on this project has been implemented for the first time and the attached video links were referred to understand and implement the same.
1. Server-Side Rendering [official document](https://angular.io/guide/universal) and below video was reffered.
 
<a href="https://www.youtube.com/watch?v=MxllVrf3y9o&t=151s" target="_blank"><img src="https://i.ytimg.com/vi/MxllVrf3y9o/hqdefault.jpg?sqp=-oaymwEcCPYBEIoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDd3LzdcYMQJztYOxn8r5OHDFXw0A" 
alt="Angular Universal" width="240" height="180" border="10" /></a>
 
2. Deployment on Heroku -- 
 
<a href="https://www.youtube.com/watch?v=SDvoYXCxBqY" target="_blank"><img src="https://i.ytimg.com/vi/SDvoYXCxBqY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDUtU--pBjPo_B5r3KZNvlv_-4sxg" 
alt="Heroku deployment" width="240" height="180" border="10" /></a>
 
<a href="https://www.youtube.com/watch?v=HWBSSC7Vbg0" target="_blank"><img src="https://i.ytimg.com/vi/HWBSSC7Vbg0/hqdefault.jpg?sqp=-oaymwEcCPYBEIoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAoY6Alp2x_85Cec0rJ-l0wdMoYlQ" 
alt="Heroku deployment" width="240" height="180" border="10" /></a>
 
3. Creating a readme file with images and other markups, following [link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is referred as a cheat sheet for markdown.
 
---
 
###About the project
 
[Live Demo](https://spacexdata-mayank.herokuapp.com)
 
This project involves an API that provided data about the SpaceX launched programs and certain filters were to be applied over that data to view them nicely.
 
The filters applied by the user are visible in the URL of the application and the call to the API happens in the background with the required filters.
 
If the page is reloaded with the previously set filters they get automatically selected in the filter section and also the API is also triggered.
 
API has been restricted to bring 50 data at max and that too is handled on the front-end with slice in-built pipe to implement the load more functionality, which shows 10 programs data at the load time and then the data cards increases gradually by 10 until all the fetched data has been shown to users.
 
Some Aria tags have also been implemented for accessibility purposes. Refer [link](https://developers.google.com/web/fundamentals/accessibility/semantics-aria) to understand usage of aria tags.
 
[Lighthouse](https://developers.google.com/web/tools/lighthouse) in chrome dev tools have been used progressively to understand and monitor the effects on Performance, Accessibility, Best Practices and SEO telimitaries of the application with gradual changes into the code.
 
---
 
Below is the sample image to test the image import from github repo for this project, which is in fact the folder structure of the project:
 
<img src="https://github.com/Mayank-Ahuja/spaceXData/blob/master/readMedata/folder-structure.PNG" width="200" height="390">
 
The above image import test was conducted to add the below Lighthouse test results for the application. Below image sizes have also been optimised using freeware online tool [TinyPng](https://tinypng.com/).
 
##### Performance Score
 
<img src="https://github.com/Mayank-Ahuja/spaceXData/blob/master/readMedata/performance-scores.png" width="890" height="500">
 
##### Accessibility Score
<img src="https://github.com/Mayank-Ahuja/spaceXData/blob/master/readMedata/accessibility-score.png" width="890" height="500">
 
##### Best Practice Score
<img src="https://github.com/Mayank-Ahuja/spaceXData/blob/master/readMedata/best-practice-score.png" width="890" height="500">
 
##### SEO Score
<img src="https://github.com/Mayank-Ahuja/spaceXData/blob/master/readMedata/seo-score.png" width="890" height="500">