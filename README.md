# Frontend Mentor -Recipe Page Solution

This is a solution to the [Recipe Page Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

Creation of a recipe page proposed by Frontend Mentor. 

## The challenge
The challenge is to create a recipe page using the right HTML semantics and accessibility.
### Screenshot

![Recipe image](image.png)

### Links

-Solution URL: [Recipe Page](https://github.com/Harena-debug/Recipe-Page)
-Live site URL: [Live demo](https://harena-debug.github.io/Recipe-Page/)

## My process

I made this recipe project as follows:

### Built with

-HTML 5 Semantics for recipe layout
-Accessibility with ARIA concepts
-CSS Flexbox for content centering
-CSS :hover and :focus for hover effect and keyboard accessibility


### What I learned
In this project, I was able to acquire the following skills:

-Accessibility with ARIA
```html
<article aria-label="Simple Omelette Recipe">
<section id="preparation" aria-labelledby="preparation-title">
<section id="ingredients" aria-labelledby="ingredients-title">
<hr aria-hidden="true">
<section id="instructions" aria-labelledby="instructions-title">
```
-La manipulation des tableaux

```html
<table class="nutrition__table">
          <tbody>
            <tr>
              <th scope="row">Calories</th>
              <td>277kcal</td>
            </tr>
            <tr>
<th scope="row">Carbs</th>
              <td>0g</td>
            </tr>
            <tr>
              <th scope="row">Protein</th>
              <td>20g</td>
            </tr>
            <tr>
              <th scope="row">Fat</th>
              <td>22g</td>
            </tr>
          </tbody>
        </table>
```
-La manipulation des tableaux avec le CSS

```css
table{
    border-collapse: collapse;
    width: 100%;
}

table th{
    font-family: var(--font-family-paragraph);
font-weight: 400;
    color: var(--paragraph-color);
   text-align: left;
   padding: 0.75rem 2rem;
   width: 50%;
}

table td{
    font-family: var(--font-family-paragraph);
    font-weight: 700;
    color: var(--title-color);
    width: 50%;
    padding: 0.75rem 2rem;
}

table tr{
    border-bottom: 1px solid hsl(30, 18%, 87%);
}

table tr:last-child{
    border: none;
}

```
### Développement continu
I was able to acquire ARIA's skills in this project but I would like to go even further. 
In the next challenge, I will use ARIA concepts better and better only if necessary. I will also try to add the CSS Grid if the challenge contains it.

### Useful resources

-[MDNWebDocs](https://developer.mozilla.org/en-US/) -This is the place that allowed me to understand and explore the concept of accessibility
-[W3Schools](https://www.w3schools.com/) -This is my playground to learn and code at the same time.

### AI collaboration

I collaborated with AIs in the following ways:

-I used the Claude and Chatgpt AIs in this project
-They helped me correct errors that blocked the results of my page


## Author

-Website -[Harena](https://github.com/Harena-debug)
-Mentor Frontend -[@Harena-debug](https://www.frontendmentor.io/profile/Harena-debug)

## Acknowledgments
A big thank you to Frontend Mentor who offered me this challenge in order to practice HTML CSS. A big thank you also to the 
mentoring in Frontend Mentor who corrected me and gave me the right path for good coding in HTML CSS.