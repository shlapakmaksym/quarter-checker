##Quarter Checker

<span>A simple JavaScript project which allows
 to identify a point quarter based on input 
 values of its 'x' and 'y' axis.</span>


Here is its code:

``` 
javascript

 if(isNaN(x) || isNaN(y)) {
    print('Some cordinate was passed with incorrect value ')
 }
 
 if(x == '' || y == '') {
    print('Some cordinate value is empty')
 }
 else if (x > 0 && y > 0) {
    document.write('Point is in the first QUARTER!');
 }
 else if (x < 0 && y > 0) {
    document.write('Point is in the second QUARTER!');
 }
 else if (x < 0 && y < 0) {
    document.write('Point is in the third QUARTER!');
 }
 else if (x > 0 && y < 0) {
    document.write('Point is in the fourth QUARTER!');
 }
 else if (x == 0 && y > 0) {
    print('Point is in 2nd or 1st QUARTER')
 }
 else if (x == 0 && y < 0) {
    print('Point is in 4th or 3th QUARTER')
 }
 else if (x == 0 && y == 0) {
    print('Point is in the beginning of ') }
 }

```