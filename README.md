# Horiseon - Module 1 challenge
A website focused on increasing your visibility, reputation and social media presence through lead generation, brand awareness, and cost managment.

This site was built using [josephkurpierz GitHub Pages](https://josephkurpierz.github.io/1code-refactor/)

![Screenshot of main website](/assets/images/Screenshot.png)

***Table of contents***
* [What I started with](#What-I-started-with)
* [How I modified the files](#How-I-modified-the-files)
* [What I learned](#what-i-learned)
* [What I struggled with](#what-i-struggled-with)
* [Why I did it](#why-i-did-it)

## What I started with 

A pre-existing website that appeared to be in working order with appropriately formatted HTML and CSS.  
The HTML file, while working, was doomed to `div` soup. 
The CSS file, also working, had an abundance of repetitive coding.
These files needed to be refactored.

It provided a good oportunity to work with semantic tags to deliver a more straight forward logical HTML file, consolidate multiple CSS selectors to a single selector, and add descriptive `alt`s to images.

## How I modified the files

Referring back to the run-buddy.html I was able to mimic some of the semantic tags such as;
```
header
footer
section
article
```
These tags allowed me to easily differentiate between the elements for a more simplistic stylesheet.  With the semantic tags in place I was able to try to **DRY** some of the **WET** CSS code by adding `class`es in a way that I could group similar elements that would recieve the same styling.

In addition to organizing and renaming the elements in html and consolidating code in CSS, `alt`s were added to the html `img`s to offer meaningful descriptions in order to provide a better experience for users in need of a screen reader.

## What I learned

- There will need to be a learned finesse to accurately and succinctly describe images.  
- When every block is a `div`, it is very challenging to keep you place.  In order to do so, many `class`es and `id`s are needed to ensure you can target the right element with CSS....which in turn makes CSS *WAY* longer than it needs to be.
- This README has its own set of rules.  I thought it was a simple text document.
- It seems like it is a much better idea to test your alterations while commenting out the part you are trying to update/replace rather than deleting it.

## What I struggled with

1. My biggest hurdle was/is the online-reputation-managment.  I tried to mimic the run-buddy trainers to capture the three part organization with orientation of left, right, left.  If I could have successfully performed that, I would have reduced even more CSS because I would not have needed the `float: right` to orient the middle article to the right and all three articles would use the same code just by altering the order of the img in the html.
2. I have also been struggling with the web pages looking different depending on screen size.  If I have a split screen it renders differently than if I go full screen.  It definitely adds some extra navigation as I only have a single monitor.
3. Writing this README is also a struggle.  I am taking a risk by writing it as a "what did Joe do?" rather than writing it as a what "What is Horiseon? and What does it do?".

## Why I did it

I worked on this Horiseon web page to practice html and CSS.  They are, at this point, foreign languages to me.  So practicing this will help me gain confidence and efficiency writing simple code.  Building this fundamental foundation is incredibly important to me as I want to be able to continually build upon it.  Onwards and upwards sombody once said.