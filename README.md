#Imperavi image cropping plugin 
Imperavi image cropping plugin based on [Image Cropper](https://github.com/fengyuanchen/cropper) which allows to crop image after uploading in [Imperavi redactor](http://imperavi.com/redactor). 

## Installation

````html
<link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.0.3/css/font-awesome.min.css" />
<link rel="stylesheet" href="cropper.css"/>
<link rel="stylesheet" href="/js/redactor/redactor.css" />
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.js"></script>
<script src="/js/redactor/redactor.js"></script>
<script type="text/javascript" src="cropper.js"></script>
<script type="text/javascript" src="imagecropper.js"></script>
````

##Usage
````javascript
$('#redactor').redactor({
  'imagecropper': {
  	'imageUpload': '/your_image_upload_script/',
  	'options': {
	    	//Image Cropper plugin options
	  	'resizable': true
  	}
  },
  'plugins': {
    ...
  	'imagecropper'
  	...
  },
});
````



