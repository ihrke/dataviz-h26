# Workshop 3 - Data visualisation I

In this workshop, we will start by discussing the figures that you have brought to get a sense of how to critically analyse a figure. This is the first step to improving your own figures.

The material in this workshop comes largely from Claus Wilkes' superb book, The Fundamentals of Data Visualzation, which is available for free online at https://clauswilke.com/dataviz/.

Other useful resources will follow.

After the break, I will also briefly introduce the projects so that you can start thinking about them 

## Follow up from workshop
We went through slides on data visualisation (part 1). There will be a second part when we next meet. When discussing tools for picking colours, I mentioned that I would list some here, so here you go - they are all fun to play with and do distinct but similar things.

https://colorbrewer2.org/
https://coolors.co/
https://www.coblind.com/color-blindness-simulator-image

I should also introduce the idea of how we define or name colours we want to use. I'll talk more about this next time but basically the most common ways are either:
* RGB values - a number between either 0 and 255 or between 0 and 1 for R(ed), G(reen), and B(lue)
* Hex values - a 6 digit hexadecimal code which represent the RGB values

You don't need to understand this in detail to use them, hex values are the easiest to use in your code as all the color generators will give you them, you can write e.g.
`ax.scatter(x, y, color="#2ca25f")`.

Hopefully, you can make some sense of this but we can discuss more in class and here is a **video**: https://www.youtube.com/watch?v=hhI4x6hx21s

## Extra hour this week
I have scheduled an extra workshop this week at 15:00-16:00 in TEO H5 5.402 (it's the big seminar room on 4th floor underneath the one we are usually in).

## Preparation for Workshop 4 and homework
We don't meet for another 2 weeks so you have time to continue working on your code. In particular, do the following...

### Open and edit a Python file once a day
I find that the barrier to coding reduces a lot once it becomes as easy to open and edit my scripts as it is to open a Word file. The best way for this to get into your "muscle memory" is just to do it regularly. I recommend that you try to just open your IDE (VSCode or Jupyter Notebook or whatever you're using) once a day, runa script and make a simple change to it (for example, if you have made a figure you could change one element of it, e.g. the color of the plot, the size of the figure, or just experiment). In the next class, when I say "everybody open a new notebook", this should be super simple and straightforward.

### Make a colourful figure
You should all have read in and plotted the `Pearson.txt` file. Try to experiment with different ways of plotting this and think about the colours that you are using. Maybe you can integrate one of the color scales we discussed. Think about what you want the colours to represent.

If you feel you have exhausted that simple dataset and want to start challenging yourself more then you could try to plot some different data (might give you ideas for your project too). The website https://www.kaggle.com/datasets has lots of free datasets. You might want to filter them to get CSV files (and easy file to read in) but then you could look at e.g.
* Titanic passengers: https://www.kaggle.com/datasets/yasserh/titanic-dataset
* Footballers: https://www.kaggle.com/datasets/whisperingkahuna/footballers-with-50-international-goals-men
* Lettuce growth stats (??): https://www.kaggle.com/datasets/jurijsruko/lettuce

Reading these in will be a bit diffrent than with the .txt file but chat.uit should help (hint: I would use the popular package `pandas` but we'll spend some more time looking at this in later classes)

### Watch video on functions and go through slides
Here is a really good video introducing functions.
https://www.youtube.com/watch?v=KW6qncswzHw

You should also look through the slides at the end of the powerpoint. Hopefully, together those resources help to eplxain the basics of functions, but again these are areas that we can discuss in class or in separate catch-up sessions if people ask for it. 

### Start thinking about possible projects
Not much to say here other than it's useful for you to start thinking what dataset you will focus on in your project. As inspriation things that previous students have used include:
* football results
* weather data
* homelessness data
* video game data
* their own spotify data
* their own strava data
* their own netflix data



