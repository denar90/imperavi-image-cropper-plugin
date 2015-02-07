#Imperavi image cropping plugin 
Imperavi image cropping plugin based on [Image Cropper](https://github.com/fengyuanchen/cropper) which allows to crop image after uploading in [Imperavi redactor](http://imperavi.com/redactor). 

## Installation
If you already use Imperavi redactor add after

````html
<script type="text/javascript" src="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.0.3/css/font-awesome.min.css"></script>
<script type="text/javascript" src="cropper.css"></script>
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
	  	'resizable' => true
  	}
  },
  'plugins': {
    ...
  	'imagecropper'
  	...
  },
});
````



