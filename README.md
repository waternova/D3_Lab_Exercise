# D3 Lab Exercise

The following lab exercise is designed to introduce you to making interactive data visualizations in D3. 

## Introduction

For both of these exercises you will need to run a python local server. You will then be able to view the progress you make in the exercise, in your browser.

1. Download the code from this repository.
2. In the command line, navigate to the folder that contains this repository.
3. Depending on which exercise you are working on, navigate to either the Basic or the Advanced Exercise folder.
4. Type the command below for whichever version of Python you are running to start a local server:
   ```
   python -m SimpleHTTPServer (for Python 2)
   python -m http.server (for Python 3)
   ```
5. Once you have the server up and running, in your browser, go to the link `0.0.0.0:8000/` to view your code in action.
6. By default the server serves the `index.html` in your folder to the browser. You can open other files from the same folder in the browser by appending the file name to the default address. For e.g. `0.0.0.0:8000/solutions.html` to open the `solutions.html` file from the same folder.

Once your server is up, start with the exercises in `app.js`. Don't forget to use your browser developer tools for debugging! 

**Note : After making changes to your file, if they do not reflect on your browser: do a hard refresh by Shift+click on the refresh button.**

## D3 Basic Exercise (start with this)

1. Open the `index.html` file and follow along with the comments in `app.js` to add the missing code and get the visualization working.
2. As you go through, try to figure out what is going on with the code. Ask the TAs if you need help. 
3. When you are done (or if you are really stuck!) look at the `app_solution.js` file.
4. If you get the basic visualization working, you can make your own modifications (add animations and interactivity, change colors, etc.) or move on to the advanced exercise below.

## D3 Advanced Exercise 

If you already have some experience in D3 or have completed the beginner exercise. Try your hand at this more advanced exercise. The original idea is from a Spring 2015 assignment by David Eicke. However, it has not been updated to use D3 v4, so... anyone who contributes that update will be appreciated.

1. Read through David's code (original.html) and look at the visualization in your browser to get a sense of what is going on in the code.
2. Implement this code using the billboardtop5.csv data.
3. Make any necessary changes to the size of the rectangles.
4. Make any other modifications you like to the animation, colors, etc.
