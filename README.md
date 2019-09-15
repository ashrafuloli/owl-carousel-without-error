# Owl Carousel v2.2.0

### Load the required stylesheet and JS:
```js
if (jQuery(".active-slider").length > 0){
  jQuery('.active-slider').owlCarousel({
    loop: true,
    autoplay: true,
    nav:false,
    //navText: ["<a><span></span></a>","<a><span></span></a>"],
    autoHeight:true,
    dots: true,
    dotsData: true,
    responsive: {
      0: {
        items: 1
      },
      600: {
        items: 1
      },
      1000: {
        items: 1
      }
    }
  });
}
```

