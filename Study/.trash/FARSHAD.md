# Global and Local Scope
```
<?php
$x = 5; // global scope
functionmyTest() {
// using x inside this function will generate an error
echo"<p>Variable x inside function is: $x</p>";
}
myTest();
echo"<p>Variable x outside function is: $x</p>";
?>
```

```
<?php
$x = 5;
$y = 10;
functionmyTest(){
global $x, $y;
$y = $x + $y;
}
myTest();
echo $y; // outputs 15
?>
```