# JS-Slider

Simple JS Slider.

### Usage in script file:

```js
  import slider from './modules/slider';
```

### Initiate example:

```js
  slider({
      next: '.offer__slider-next',
      prev: '.offer__slider-prev',
      totalCounter: '#total',
      currentCounter: '#current',
      slidePack: '.offer__slide',
      wrapper: '.offer__slider-wrapper',
      field: '.offer__slider-inner'
  });
```
  
#### Where as: 
  ##### next - next navigation button(arrow),
  ##### prev - previous navigation button(arrow),
  ##### totalCounter - total slides counter, changes text depending on number of slides,
  ##### currentCount - current slide counter, sets randomly at the page load,
  ##### slidePack - selector of slide images,
  ##### wrapper - wrapper of the slider,
  ##### field - inner wrapper for the slides
  <br>
  
### HTML example:
  
```html  
  <div class="offer__slider">
    <div class="offer__slider-counter">
        <div class="offer__slider-prev">
            <img src="icons/left.svg" alt="prev">
        </div>
        <span id="current">03</span>
        /
        <span id="total">04</span>
        <div class="offer__slider-next">
            <img src="icons/right.svg" alt="next">
        </div>
    </div>
    <div class="offer__slider-wrapper">
        <div class="offer__slider-inner">
            <div class="offer__slide">
                <img src="img/slider/pepper.jpg" alt="pepper">
            </div>
            <div class="offer__slide">
                <img src="img/slider/food-12.jpg" alt="food">
            </div>
            <div class="offer__slide">
                <img src="img/slider/olive-oil.jpg" alt="oil">
            </div>
            <div class="offer__slide">
                <img src="img/slider/paprika.jpg" alt="paprika">
            </div>
        </div>
    </div>
  </div>
```
