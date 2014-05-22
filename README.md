parallaxScroll
==============

A debounced parallax scrolling plugin for jQuery.

###Initializing:

The HTML:

```html
<div id="parallaxWrap">
    <div class="section" data-background="my-special-bg.png">
        <div class="sectionContent">
            <!-- Your content goes here -->
        </div>
    </div>
    <div class="section" data-background="my-special-bg.png">
        <div class="sectionContent">
            <!-- Your content goes here -->
        </div>
    </div>
    <div class="section" data-background="my-special-bg.png">
        <div class="sectionContent">
            <!-- Your content goes here -->
        </div>
    </div>
</div>
```

The Javascript:

```javascript
$('#parallaxWrap').prallaxScroller({
    'parallaxIntensity': 0,
    'singleBG': false
});
```


###Options:

```
'parallaxIntensity': [0-9]
```
**Default: 0**

*Change the intensity of the effect, the higer the number the more movement the background will have*
```
'singleBG': [true|false]
```
**Default: false**

*Whether each section has it's own background image or they share a single background image. For true, omit the data-background attribute for all sections except the primary*