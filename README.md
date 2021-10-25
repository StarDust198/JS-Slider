# JS-Slider

Simple JS Slider.

### Usage in script file:

```js
  import slider from './modules/slider';
```

### Initiate example:

```js
  slider({
      slidePack: '.main-slider-item',
      wrapper: '.main-slider-wrapper',
      field: '.main-slider',
      direction: 'V',
      timer: 10,
      indicators: true
  });
```
  
### Where as: 
<br>

  #### Necessary fields:
  ##### slidePack - selector of slide images/divs,
  ##### field - selector of slider field, containing wrapper with slides,
  ##### wrapper - selector of inner wrapper for the slides,
  <br>
  
  #### Needed if arrow buttons avaible, can be used separately:
  ##### next - selector of next navigation button/arrow selector,
  ##### prev - selector of previous navigation button/arrow selector,
  <br>
  
  #### Needed if on-page slide-counters avaible, can be used separately:
  ##### totalCounter - selector of total slides counter, changes text depending on number of slides,
  ##### currentCount - selector of current slide counter,
  <br>
  
  #### Other:
  ##### indicators - false(def.)/true - creates dot-indicators allowing to pick slide,
  ##### direction - default is horizontal, use 'V' or 'vertical' for vertical slider direction,
  ##### timer - time in seconds between slideshow change, default is off
  <br>
  
### HTML example:
  
```html  
  <div class=main-slider>
    <div class="main-slider-wrapper">
      <div class=main-slider-item>
        <img src=assets/img/main-1.png alt>
      </div>
      <div class=main-slider-item>
        <img src=assets/img/main-2.png alt>
      </div>
    </div>
  </div>
```