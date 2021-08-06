# Code Key
Code key is a frame work of css like bootstrap and tailwind css and etc it's has many class like btn, container and card etc, It's has the version 1.6, it's used for making a website very stylish, quickly and responsively.
    <link href="https://muhammedraiyaan2.github.io/codekey/codekey.css" rel="stylesheet">
## Cdn Link
Paste this code in the head tag
```bash
<link rel="stylesheet" href="https://muhammedraiyaan2.github.io/codekey/codekey.css">
```
## Components
- Text color
- Background color
- Border color
- Container
- Text size
- Btn
- Input
- Card
- Navbar
- Navbar sticky
- Dropdown
- Footer
### Text Color
---
The text color will change the text color that you wanted to add in your website, In the given below code I add text red color what you want you can add that color name
```bash
  <h1 class="text-red">Testing!</h1>
```
  <h1 class="text-red">Testing!</h1>
  
### Background Color
---
Background color what ever you want 
the background you can select, I written it red you select your option

```bash
<div class="bg-red">
<h1>Testing!
</div>
```
<div class="bg-red">
<h1>Testing!
</div>
    
### Border Color
---
Border color it has background and the border for example you have created a button and the button background is blue and the border of the button is unset and you want set what will you do you will add css but code key is provinding a border color 

```bash
<button class="border-blue">Button!</button>
```
<button class="border-blue">Button!</button>
### Container
---
Container is a box like full width or fixed width and you can add a background to that and the height is cover the content

For full width container

```bash
<div class="container con-width-large bg-red">
<h1 class="text-white">Testing</h1>
</div>
```
<div class="container con-width-large bg-red">
<h1 class="text-white">Testing</h1>
</div>

For fixed width container
```bash
<div class="container con-width-small bg-blue">
<h1 class="text-white">Testing</h1>
</div>
```
<div class="container con-width-small bg-red">
<h1 class="text-white">Testing</h1>
</div>

### Text size
---
The text size is up to 1 to 5
```bash
<h1 class="text-1">Heading!</h1>
```
```bash
<h1 class="text-2">Heading!</h1>
```
```bash
<h1 class="text-3">Heading!</h1>
```
```bash
<h1 class="text-4">Heading!</h1>
```
```bash
<h1 class="text-5">Heading!</h1>
```
<h1 class="text-1">Heading1</h1>
<h1 class="text-2">Heading2</h1>
<h1 class="text-3">Heading3</h1>
<h1 class="text-4">Heading4</h1>
<h1 class="text-5">Heading5</h1>

### Button 
---
Button are mustly used in a website with different designs, code key is providing a square button circle button and transition button
### Box button
---
Box button are normal button that you see in a website

Large button
```bash
<button class="btn-large-bg-blue">Button large!</button>
```
<button class="btn-large-bg-blue">Button large!</button>


Medium button
```bash
<button class="btn-medium-bg-blue">Button medium!</button>
```
<button class="btn-medium-bg-blue">Button medium!</button>

Small button
```bash
<button class="btn-small-bg-blue">Button small!</button>
```
<button class="btn-small-bg-blue">Button small!</button>

### Button size
---
Button size is very important for a button and you can set the button size with code key

For large buttons
```bash
<button class="btn-large border-grey">button large!</button>
```
<button class="btn-large border-grey">button large!</button>

For medium buttons
```bash
<button class="btn-medium border-grey">Button Medium!</button>
```
<button class="btn-medium border-grey">Button Medium!</button>

For small buttons
```bash
<button class="btn-small border-grey">button small!</button>
```
<button class="btn-small border-grey">button small!</button>

### Circle transition button
---
The circle transition button is 
when hover the button it change to any color, first it will have a white background and when you hover it will change color what you want to change Note: first background white color you can't change the second color you can change
```bash
<button class="btn-circle-bg-white-blue btn-medium">Button medium transition</button>
```
<button class="btn-circle-bg-white-blue btn-medium">Button medium transition</button>


### Box transition button 
It's same like the circle transition button but this box in shape
```bash
<button class="btn-bg-white-purple btn-large">Button large!</button>
```
<button class="btn-bg-white-purple btn-large">Button large transition!</button>

### Circle Button
Circle button is a button shape circle with any background color
```bash
<button class="btn-circle-bg-orange btn-small">Button small circle</button>
```
<button class="btn-circle-bg-orange btn-small">Button small circle</button>

### Input
Input tag or input in the website is used for a form or a email and address and phone number etc, input is a main in a website to attract the user, code key is providing you a input style there are three types large, medium and small input

For large input
```bash
<input type="text" class="input-large">
```
<input type="text" class="input-large">

For medium input
```bash
<input type="text" class="input-medium">
```
<input type="text" class="input-medium">

For small input
```bash
<input type="text" class="input-small">
```
<input type="text" class="input-small">

### Card
Card is a box where you add some of the detail, the card is used for like profile and shoping in a ecommerce website
### Card align
Card align is very important for multiply card to set in a column, You must enter the card align, the card align is up to 1 to 5 totaly you can set it 5 cards in a column

```bash
  <div class="card card-align-5 border-blue"></div>
```
### Card title class
The card title is very important compnent for a card there are two types of title one is text another one is image.

For text title
```bash
  <div class="card card-align-1 border-blue">
   <h1 class="card-title-text">Heading</h1>
  </div>
```
For image title
```bash
  <div class="card card-align-1 border-blue">
   <img src="dummy.jpg" alt="dummy image" class="card-title-image">
  </div>
```
For multiply card

Note:
In the code the align is 3 you can change to your option
```bash
  <div class="card card-align-3 border-blue">
   <img src="dummy.jpg" alt="dummy image" class="card-title-image">
   <h1 class="card-title-text">Heading!</h1>
  </div>
```
### Navbar
Navbar is a very important part of a website for heading and tell us about that where is home contact and about etc.

navcom is a class for title of the navbar or the brand or the company
```bash
<nav class="navbar bg-black">
<li class="navcom text-white">Title!</li>
<ul>
<li class="text-white"><a href="#home">Home</a></li>
<li class="text-white"><a href="#services">Services</a></li>
<li class="text-white"><a href="#about us">About us</a></li>
<li class="text-white"><a href="#contact us">Contact Us</a></li>
</ul>
</nav>
```
### Navbar Sticky
Navbar sticky is same like navbar but it's stick on the top of the website when you scroll it will not go it will stick in the top.
```bash 
<nav class="navbar-stick bg-black">
<li class="navcom text-white">Title!</li>
<ul>
<li class="text-white"><a href="#home">Home</a></li>
<li class="text-white"><a href="#services">Services</a></li>
<li class="text-white"><a href="#about us">About us</a></li>
<li class="text-white"><a href="#contact us">Contact Us</a></li>
</ul>
</nav>
```
### Dropdown
Dropdown is a set of value to select one of the value.
```bash
<select class="dropdown text-white border-lightpurple">
<option>Selec the car</option>
<option>volvo van</option>
<option>benz</option>
<option>bmw</option>
<option>farreri</option>
<option>rolls races</option>
</select>
```
### Footer 
Footer is used for contact or coprights or terms and policy etc.


```bash
<div class="footer bg-black">
<h3>&copy Copright@codekey</h3>
</div>
```
<h5 align="center">&copy Copyright@CodeKeydocumentation
