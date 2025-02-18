# Accessibility practise
Practise project for Merkle.

The project contains an html file with many accessibility errors. With every step or exersice the idea is to focus in one type of accessibity error and fix it. 

The page is a personal page. 

## How to complete the exercises

1. Read the description
2. Analyze the website for the guidelines given
3. List the accessibility issues
4. Fix the issues


## Exercises
### 0. Language

Change the language of the document to english:
    

### 1. Images

the alt of the image quarks.jpg was missing
<img src="quarks.jpeg" alt="Image of a proton is composed of two up quarks, one down quark, and the gluons that mediate the forces binding them together.">

the alt of the image products is too long
<img src="products.webp" alt="Sky offers broadband, TVs, TV packs to watch football and many more product">

the alt of the sky logo image is no needed as its decorative
<img src="sky%20logo.png" alt="">


### 2. Headings

change the type of the tittles from <div class="h2">Team Members</div> to <h3></h3>

### 3. Links

rm style="text-decoration: none; cursor: default" 
add the aria label aria-label="Read mode about Manresa"

### 4. Focus

rm 
<style>
a {
outline: none;
}
</style>

### 5. Tables

add the aria 
 <table aria-labelledby="Beer prices around the world table">
add row headers
add column headers

### 6. Forms

surround the buttons with the labels
<label>
<input type="checkbox" name="friday" />
Friday </label>

and
<div class="field-group">
            <label id="office-days-label">When do you come to the office?</label>
            <div class="checkbox-group" aria-labelledby="office-days-label">

### 7. Landmarks


