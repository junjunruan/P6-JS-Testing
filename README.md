# Project 6: Feed Reader Testing with Jasmine

This is the sixth project of Udacity Front-End Web Developer Nanodegree. Tests should be written using Jasmine to make sure a udacity blog RSS feed works correctly. Click [here](http://junjunruan.github.io/P6-JS-Testing) to visit the website.

Here is the [link](https://www.udacity.com/course/viewer#!/c-nd001/l-3442558598/m-3380619337) to the rubric for the class.

- Required courses: [JavaScript Testing](https://www.udacity.com/course/ud549)

- Required project asset: https://github.com/udacity/frontend-nanodegree-feedreader

- Required Technics: Jasmine, JavaScript, Test-driven Development, Red-Green-Refactor Cycle

Github folders:

- ./js/app.js: application code

- ./jasmine/spec/feedreader.js: testing code

##Test Contents:

1. Test suite: RSS Feeds

  * Write a test to make sure that the allFeeds variable has been defined and that it is not empty.
 
  * Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.

  * Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

2. Test suite: The menu

  * Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.

  * Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

3. Test suite: Initial Entries

  * Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.

4. Test suite: New Feed Selection

  * Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
  
  
 In order to see if tests are working, we can edit the corresponding code in app.js and make tests fail. In the end, all tests should pass.
 
<img src="http://i.imgur.com/s5El0WL.png"/>

