# Accessibility practise

The project contains a html file with many accessibility errors. With every step the idea is to focus in one type of accessibility error and fix it. 

To run the project you need to install python:

brew install python

to execute a http server (to run the automated tests):

python3 -m http.server

(execute this in the folder)



## Exercises
### 0. Language

The focus of this exercise is to improve the accessibility of the speech when reading the page

### 1. Images

The focus of this exercise is to improve the accessibility of the images. To do this you have to check with the screen reader the accessibity of the
different images and decide what are the errors that need to be fixed.

There are 3 errors.

check this page to write good alt texts -> https://accessibility.huit.harvard.edu/describe-content-images

### 2. Headings

The focus of this exercise is to improve the accessibility of the headings. To do this you will have to check with the screen reader if something is
missing. 

The expected behaviour of the screen reader with the titles is that the reader says "Heading level ..."

### 3. Links

The focus of this exercise is to improve the accessibility of the links. see https://www.w3.org/WAI/WCAG21/Techniques/aria/ARIA8
To check that you will need to try the with color blindness simulator and see check if you find the link. Also you will need to check with the screen 
reader and guess what is the link supposed to do.

### 4. Focus

The focus of this exercise is to improve the accessibility of keyboard navigation. You will have to try to move around with the tab key.

### 5. Tables

The focus of this exercise is to improve the accessibility of the beer price table in the webpage. To locate the table you can use 
VO + Command + T (VO by deafult is cntl+option)

To move around the table is VO+arrows
To read the current column header VO+C
To read the current row header VO+R

Try to improve the location when you are inside the table and using the commands to know the current column and row
The caption of the table is missing also

### 6. Forms

The focus of this exercise is to improve the accessibility of the form in the webpage. The form fields are not properly associated with their labels,
when reading it with the screen reader it's difficult to understand what are you filling in the form.


### 7. Colours

Try with a accessibility checker tool if the colours have enough contrast


### 8. More

There are many other things that you can do to improve the accessibility, try your best!