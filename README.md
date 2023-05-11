# sliderJS
A conventional JavaScript library for creating a slides.

# Overview 

```
// For texts.
let listNames = ["Yer", "Renzter", "Nenyer", "Yerenzter"];

// For images.
let listImages = ["couple1.png", "couple2.png", "couple3.png", "couple4.png"];

// Example when we querying HTML elements.
let names = document.querySelector("#names");
let images = document.querySelector("#images");

// Instantiate a Slider Class from sliderJS
let slideName = new Slider(listNames);
let slideImage = new Slider(listImage);

// Events when previous and next input button is clicked.

function OnPrevious() {
    names.textContent = slideName.Previous();
    images.src = slideImage.Previous();
}

function OnNext() {
    names.textContent = slideName.Next();
    images.src = slideImage.Next();
}
```
