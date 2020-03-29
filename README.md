# saxxtext.js :fire:
*A tiny (~0.75kb) javascript library for
cool in & out text & hover animations.*

```javascript
// Start baffle on any element(s).
setSaxxAnimation ( 'h1' , 'animated heartBeat' ) ;
setSaxxMouseEffect ( 'h1' , 'animated heartBeat' , "black", 'blue' ) ;

```

## Installation
To get saxxtext, either download the latest release and include
it in your markup, or install with NPM.
### *npm*
```sh
npm install --save saxxtext
```
### *vanillaJS*
```html
<script src="https://iamharsh.design/saxxtext/lib/saxxtext.js"></script>
```

## Usage
To use saxxtext, the elements you wanna animate have to be inside a parent tag
and just by adding the few lines of code mentioned below can do the job.
```javascript
// add to html file

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
<script src="https://iamharsh.design/saxxtext/lib/saxxtext.js"></script>

//html example

<div class="elementbody">
<h1>H</h1>
<h1>A</h1>
<h1>R</h1>
<h1>S</h1>
<h1>H</h1>
</div>

// add to style.css .
.elementbody { display : flex; }

// add to javascript file.
setSaxxAnimation ( 'h1' , 'animated heartBeat' ) ;
setSaxxMouseEffect ( 'h1' , 'animated heartBeat' ,'black','blue' ) ;

```

Animation Options
This js library uses <a href='https://daneden.github.io/animate.css/'>animate.css</a> for animations so we
support all the animations provided by <a href='https://daneden.github.io/animate.css/'>animate.css</a>.
So you can visit their website and see what animation suits you and can use it.

## Demo
<h3><a href="https://saxxtext.iamharsh.design/#demo">Click here to see demo</a><h3>

## Author
<a href='https://iamharsh.design/'>Harsh Vardhan Goswami</a>
## Contribution
You guys can also contribute to this project what you have to do is just fork this repo and then make a pull request and i will merge it. Its simple af.
