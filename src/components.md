
<html>
<head>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
</head>
<body>


# Bootstrap Components Review

This is intended as a reference guide for the use of bootstrap components.

As a side note, Bootstrap requires that you include the following:
```<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

 <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    
<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  
```

---

## 1. Glyphicons

All the available glyphicons [can be found here](https://glyphicons.bootstrapcheatsheets.com), you only require to copy-paste the code.

Here are some of the best ones:

<i class="glyphicon glyphicon-ok"></i> ok
````
<i class="glyphicon glyphicon-ok"></i>
````


<i class="glyphicon glyphicon-remove"></i> remove
````
<i class="glyphicon glyphicon-remove"></i> 
````
<i class="glyphicon glyphicon-user"></i> user

```
<i class="glyphicon glyphicon-user"></i>
```
<i class="glyphicon glyphicon-home"></i> home

```
<i class="glyphicon glyphicon-home"></i>
```
<i class="glyphicon glyphicon-camera"></i> camera

```
<i class="glyphicon glyphicon-camera"></i>
```
<i class="glyphicon glyphicon-search"></i> search

```
<i class="glyphicon glyphicon-search"></i>
```
<i class="glyphicon glyphicon-download"></i> download

```
<i class="glyphicon glyphicon-download"></i>
```
<i class="glyphicon glyphicon-upload"></i> upload

```
<i class="glyphicon glyphicon-upload"></i>
```
<i class="glyphicon glyphicon-copyright-mark"></i> copyright-mark

```
<i class="glyphicon glyphicon-copyright-mark"></i>
```
The `aria-hidden="true"` atribute hides the glyphicosn from screenreaders.

## 2. Dropdowns

The `class="dropdown" ` as a div attribute creates a dropdown menu, meanwhile a `class = dropup` creates a dropup menu. a ` class= ".dropdown-menu-right"` added to the default menu clas, will **aling the items to the right**

<div class="dropup">
  <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Dropup
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenu2">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li role="separator" class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>

A li element inside the menu with a `class="dropdown-header"` will create a text for separating menu elements, and a ` <li role="separator" class="divider"></li>` will create a divider.

## 3 Buttons

The `class = "btn"` for buttons  will create bootstrap buttons and `class = "btn-group` div will wrap them.
<div class="btn-group" role="group" aria-label="...">
  <button type="button" class="btn btn-default">Text</button>
  <button type="button" class="btn btn-default">Text</button>
</div>


Meanwhile, `<div class="btn-toolbar"> ` will add a wrap for the btn-group divs.

<div class="btn-toolbar" role="toolbar" aria-label="...">
  <div class="btn-group" role="group" aria-label="...">
   <button type="button" class="btn btn-default">1</button>
    <button type="button" class="btn btn-default">2</button>
 </div>
  <div class="btn-group" role="group" aria-label="...">
   <button type="button" class="btn btn-default">3</button>
  </div>

</div>

If the div that contains the buttons has the `btn-group-vertical ` class, it will put the buttons vertically.


  <div class="btn-group-vertical" role="group" aria-label="...">
   <button type="button" class="btn btn-default">1</button>
    <button type="button" class="btn btn-default">2</button>
 </div>
  


To separate dropdown buttons from the menu, you have to group **two** buttons and one of them should have the`dropdown-toogle`class.

  <div class="btn-group">
  <button type="button" class="btn btn-danger">Action</button>
  <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    <span class="caret"></span>
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <ul class="dropdown-menu">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li role="separator" class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>

## 4 Navbar



<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  
 <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
</body>
</html>