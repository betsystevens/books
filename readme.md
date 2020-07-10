# O'Really Book Site 

A mock book site to practice the bootstrap components presented in the coursera course:  
*"Front-End Web UI Frameworks and Tools: Bootstrap 4"*

## Dependencies
- Bootstrap depends on jquery and popper.js
- Install bootstrap, jquery and popper.js
```
$ npm install bootstrap --save
$ npm install jquery popper.js --save
```
- Add the bootstrap link in the ```<head>``` section of index.html 
```
<head>
  ...
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
  ...
</head>
```
- At bottom of page, just before the ```</body>``` tag, add the following code.

```
<!-- jQuery first, then Popper.js, then Bootstrap JS. -->
<script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
<script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
```
- Use Icon Fonts with font-awesome and bootstrap-social
```
$ npm install font-awesome@4.7.0 --save
$ npm install bootstrap-social@5.1.1 --save
```
- Add to the ```<head>``` section of index.html
```
<link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css">
<link rel="stylesheet" href="node_modules/bootstrap-social/bootstrap-social.css">
```