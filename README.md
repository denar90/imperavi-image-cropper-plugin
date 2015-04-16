#Imperavi image cropping plugin 
`Imperavi image cropping plugin` based on [Image Cropper](https://github.com/fengyuanchen/cropper) which allows to crop image after uploading in [Imperavi redactor](http://imperavi.com/redactor). 

##Getting started

###Quick start

Four quick start options are available:

* [Download the latest release](https://github.com/denar90/imperavi-image-cropper-plugin/archive/master.zip).
* Clone the repository: git clone https://github.com/denar90/imperavi-image-cropper-plugin.git.
* Install with [Bower](http://bower.io): `bower install imperavi-imagecropper`.

## Installation

````html
<link rel="stylesheet" href="path/to/font-awesome.min.css" />
<link rel="stylesheet" href="path/to/cropper.min.css"/>
<link rel="stylesheet" href="path/to/redactor.css" />
<script src="path/to/jquery.js"></script>
<script src="path/to/redactor.js"></script>
<script src="path/to/cropper.min.js"></script>
<script src="path/to/imagecropper.js"></script>
````

##Usage
````javascript
$('#redactor').redactor({
  'imagecropper': {
  	'imageUpload': '/your_image_upload_script/',
  	'modalWidth': 700, //additional option
    'buttonCropText': 'Crop', //additional option
    'buttonSaveText': 'Save without cropping', //additional option
  	'croppingOptions': {
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

##Options

#### modalWidth
* type: String | Number
* default: 700

#### buttonCropText
* type: String
* default: 'Crop'

#### buttonSaveText
* type: String
* default: 'Save without cropping'

#### options
* type: Object
* All allow [Image Cropper](https://github.com/fengyuanchen/cropper) options
