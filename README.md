# upimage

Upload photo and images with Flutter.

## Getting Started

Set up a PHP file like this:

```
<?php

    $image = $_POST['image'];
    $name = $_POST['name'];

    $realImage = base64_decode($image);
    
    file_put_contents($name, $realImage);
```
