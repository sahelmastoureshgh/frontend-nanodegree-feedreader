# Project Overview
Feedreader Testing
In this project, test cases has been written with Jasmine framework for diffrent functinality of a web-based application that reads RSS feeds.

#Here are test cases:
1.loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2.loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3.new test suite named "The menu".
4.Ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5.Ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6.Ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.
7.Ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.
https://github.com/sahelmastoureshgh/frontend-nanodegree-feedreader
This project was made with Jasmine framework

How it see test results

When page loads (index.html), the test results will be displayed 
