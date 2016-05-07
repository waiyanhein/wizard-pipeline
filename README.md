# wizard-pipeline
This is the jquery wizard plugin. Fully customizable. JQuery is required to use this plugin.

###Include jquery file and wizard-pipeline.min.js in your html

###This is the example of html and javascript

```html
  <ul class="wizard-container">
		<li active='0'>
			<a href="">
				<strong>Step 1</strong>
				<p>Step 1 title</p>
			</a>
		</li>
		<li active='1'>
			<a href="">
				<strong>Step 2</strong>
				<p>Step 2 title</p>
			</a>
		</li>
		<li active='0'>
			<a href="">
				<strong>Step 3</strong>
				<p>Step 3 title</p>
			</a>
		</li>
		<li active='0'>
			<a href="">
				<strong>Step 4</strong>
				<p>Step 4 title</p>
			</a>
		</li>
	</ul>
```	

Set active="1" attribute to li element to set current active step. 

	$(function(){
	     $('.wizard-container').wizardPipeline()
	})
	
###This is the example of what you will get
![alt tag](https://github.com/waiyanhein/wy-wizard/blob/master/sample.png)

###Options

#####1. previous_step_bg
  Set the background color of the previous or passed wizard step li.

#####2. active_step_bg
  Set the background color of the current wizard step li.
  
#####3. next_step_bg
  Set the background color of the coming wizard step li.
  
#####4. text_color
  Set the text color. Default is white.
  
#####5. height
  Set the height. Default is "60px".
  
#####6. width
  Set the padding. Default is "130px".
  
#####7. padding
  Set the padding. Default is "10px".
  
#####8. border_radius
  Set the radius of the border. Default is "5px".
  
###Exapmle of using options
```html
$selector.wizardPipeline({ width : "200px" })
```
