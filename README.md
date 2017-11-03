# Toggle-Checkbox using Pure HTML and CSS3
![Demo Gif](http://yuhlau.github.io/toggle-checkbox/demo.gif)  
Toggle-Checkbox is a mobile-like toggle switch on Webpages based on purely HTML and CSS3. It is based on checkbox input so you can capture its value just like normal form input. You can also easily change its layout using simply HTML and CSS. It supports most of the modern desktop and mobile browsers. For more specific information, plesase have a look at the Browser Support section.  
[Demo Page](http://yuhlau.github.io/toggle-checkbox/)  
  
If you need to support older browsers or want flexibility in more details, I am planing on a jQuery version. Please stay tuned and I will update this section when it is published.  
## Features
* 100% Pure HTML and CSS3 rendered  
* Checkbox input based. You can easily check the value at local or server side like normal form input  
* Flexibility in toggle switch's size and colour without lost of details  
* Change layout using purely HTML and CSS  
  
## Installation
1. Extract the css folder and its content to your site directory  
2. add the following code inside the ```<head>``` section of the webpage.  
``` html
<link href="css/toggle-checkbox.css" rel="stylesheet" type="text/css" />
```  
## Usage 
Simply copy the code to the desired position. For more usage examples visit the [Demo Page](http://yuhlau.github.io/toggle-checkbox/).  
### 1. Simple Toggle-Checkbox element  
``` html
<label class="toggle-checkbox">  
  <input type="checkbox" />  
  <div class="toggle-bg"><div class="toggle-btn"></div></div>  
</label>
```  
  
### 2. Wider Toggle-Checkbox element (With auto height calculation) 
To have wider toggle switch, set the width of the ```class="toggle-bg"``` element, the height of the toggle switch will be calculated correspond to the width automatically.  
``` html
<label class="toggle-checkbox">  
  <input type="checkbox" />  
  <div class="toggle-bg" style="width: 100px"><div class="toggle-btn"></div></div>  
</label>
```  
  
### 3. Custom Layout Toggle Checkbox
By changing the ```border``` and ```background-color``` property of the ```class="toggle-bg"``` and ```class="toggle-btn"``` element , you can customize the layout.  
  
### 4. Use fixed height instead of auto-calculation 
If you want to have a toggle switch bar with fixed height, you can add the class ```toggle-fixedheight``` to the ```class=toggle-checkbox``` element and specific your own height at the ```class=toggle-bg``` element".  
``` html
<label class="toggle-checkbox toggle-fixedheight">  
  <input type="checkbox" />  
  <div class="toggle-bg" style="height: 30px"><div class="toggle-btn"></div></div>  
</label>
```  
  
### 5. Fixed text inside toggle switch button
``` html
<label id="fixedheight-toggle-checkbox-textbtn" class="toggle-checkbox">  
  <input type="checkbox" />  
  <div class="toggle-bg"><div class="toggle-btn">O</div></div>  
</label>
```  
If you have applied fixed height to the toggle switch, remember to set the line-height of ```class=toggle-bg``` element as well  
  
### 6. Dynamic text inside toggle switch button
``` html
<label id="fixedheight-toggle-checkbox-dynamictextbtn" class="toggle-checkbox">  
  <input type="checkbox" />  
  <div class="toggle-bg">  
    <div class="toggle-btn">  
      <span class="toggle-btn-yes">Y</span>  
      <span class="toggle-btn-no">N</span>  
    </div>  
  </div>  
</label>
```  
  
### 7. Dynamic text at toggle switch background
``` html
<label id="fixedheight-toggle-checkbox-with-text" class="toggle-checkbox toggle-fixedheight">  
  <input type="checkbox" />  
  <div class="toggle-bg">  
    <span class="toggle-bg-texton">On</span>  
    <div class="toggle-btn"></div>  
    <span class="toggle-bg-textoff">Off</span>  
  </div>  
</label>
```  
Since text at background usually span a longer width than its containing space, you can apply Wider Fixed Height to the element as well
  
## Browser Support
* Google Chrome (latest)
* Mozilla Firefox (latest)
* Apple Safari (latest)
* Microsoft Edge (latest)
* Internet Explorer (9+, IE9 has no transition effect)
* Opera (Testing)
* Android Browser (latest)
* Google Chrome on Android (latest)
* Apple Safari on iOS (latest)
* Google Chrome on iOS (latest)
  
## History
* 27 Jan, 2016, Version 1.0.0
  * Rebuild repository
* 12 Jan, 2016, Version 1.0.0
  * First published
  
## License
Copyright (c) Yu H. 
Published under The MIT License (MIT)
