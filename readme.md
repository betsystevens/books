# O'Really Book Site 

A mock book site to practice the bootstrap components presented in the coursera course:  
*"Front-End Web UI Frameworks and Tools: Bootstrap 4"*

---
- Bootstrap depends on jquery and popper.js
- Install bootstrap, jquery and popper.js
```
$ npm install bootstrap --save
$ npm install jquery popper.js --save
```
- Add link to index.html
```
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
```
- At bottom of page, just before the end of the body tag, add the following code.

```
<!-- jQuery first, then Popper.js, then Bootstrap JS. -->
<script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
<script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
```