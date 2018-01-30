### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

##### How I Optimized the Page
1. Re-sized the thumbnail image
2. Write the Necessary Style as inline as an Inline Script
3. Add Media in the Script
4. Load the Google Font using Web Font Loader instead of the old way [here](https://github.com/typekit/webfontloader)

##### Results in PageSpeed Insights!
![Mobile Test](https://github.com/Sohaibzh/Udacity-FEND-Misk-Project4/blob/master/img/IndexTest1.png) 
![Desktop Test](https://github.com/Sohaibzh/Udacity-FEND-Misk-Project4/blob/master/img/IndexTest2.png) 



##### How To Run the Project

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

#### Part 2: Optimize Frames per Second in pizza.html

##### How I Optimized the Page
1. Re-sized the Pizza image
2. Changed most of **document.querySelector** to **document.getElementById()** [Reference](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById/).
3. Saved the Array length outside the loops
4. Created a local variable to save **document.getElements** outside the loops

##### Results After Optimization
![Load Time](https://github.com/Sohaibzh/Udacity-FEND-Misk-Project4/blob/master/img/pizzaTest1.png) 
![FPS](https://github.com/Sohaibzh/Udacity-FEND-Misk-Project4/blob/master/img/pizzaTest2.png) 


#### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
