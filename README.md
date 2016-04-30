# VergeGallery
---
Small jQuery plugin to show all pictures from specified container in a floating box.

## Usage
---
```javascript
$(function() {
    $('selector').VergeGallery();
});
```
## Example
---
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
    <script type="text/javascript" src="verge_gallery.min.js"></script>
    <title>Gallery</title>
</head>
<body>
    <div class="gallery">
        <img width="50" height="50" src="1.jpg">
        <img width="50" height="50" src="2.jpg">
        <img width="50" height="50" src="3.jpg">
        <img width="50" height="50" src="name.jpg">
        <img width="50" height="50" src="another_name.jpg">
    </div>
    
    <script type="text/javascript">
        $(function() {
            $('.gallery').VergeGallery();
        });
    </script>
</body>
</html>
```
