# Math Functions Reference

| Function | Description | Syntax | Arguments | Example |
|----------|------------|--------|-----------|---------|
| acos | Returns the inverse cosine of a value in radians. | `acos(value)` | value — cosine of an angle in radians | `acos(0.5) → 1.0471975511966` |
| asin | Returns the inverse sine of a value in radians. | `asin(value)` | value — sine of an angle in radians | `asin(1.0) → 1.5707963267949` |
| atan | Returns the inverse tangent of a value in radians. | `atan(value)` | value — tan of an angle in radians | `atan(0.5) → 0.463647609000806` |
| atan2 | Returns the inverse tangent of dy/dx considering quadrant. | `atan2(dy, dx)` | dy — y difference<br>dx — x difference | `atan2(1.0, 1.732) → 0.523611477769969` |
| ceil | Rounds a number upwards. | `ceil(value)` | value — a number | `ceil(4.9) → 5` |
| clamp | Restricts a value to a range. | `clamp(min, input, max)` | min — lower bound<br>input — value<br>max — upper bound | `clamp(1,5,10) → 5` |
| cos | Returns cosine of an angle. | `cos(angle)` | angle — radians | `cos(1.571) → 0.0007963` |
| degrees | Converts radians to degrees. | `degrees(radians)` | radians — number | `degrees(π) → 180` |
| exp | Returns exponential of a value. | `exp(value)` | value — number | `exp(1) → 2.71828` |
| floor | Rounds a number downwards. | `floor(value)` | value — number | `floor(4.9) → 4` |
| ln | Returns natural logarithm. | `ln(value)` | value — number | `ln(1) → 0` |
| log | Logarithm with base. | `log(base, value)` | base — number<br>value — number | `log(2,32) → 5` |
| log10 | Base-10 logarithm. | `log10(value)` | value — number | `log10(100) → 2` |
| max | Returns largest value. | `max(v1, v2, …)` | values — numbers | `max(2,10.2,5.5) → 10.2` |
| min | Returns smallest value. | `min(v1, v2, …)` | values — numbers | `min(20.5,10,6.2) → 6.2` |
| pi | Returns π. | `pi()` | — | `pi() → 3.14159` |
| radians | Converts degrees to radians. | `radians(deg)` | deg — number | `radians(180) → 3.14159` |
| rand | Random integer in range. | `rand(min,max[,seed])` | min — int<br>max — int<br>seed — optional | `rand(1,10) → 8` |
| randf | Random float in range. | `randf([min,max,seed])` | min/max — float<br>seed — optional | `randf(1,10) → 4.59` |
| round | Rounds to decimal places. | `round(value[,places])` | value — number<br>places — optional | `round(1234.567,2) → 1234.57` |
| scale_exponential | Maps value using exponential curve. | `scale_exp(v,dmin,dmax,rmin,rmax,e)` | domain + range + exponent | `scale_exp(5,0,10,0,100,2) → 25` |
| scale_linear | Linear interpolation. | `scale_linear(v,dmin,dmax,rmin,rmax)` | domain + range | `scale_linear(5,0,10,0,100) → 50` |
| scale_polynomial | Maps value using polynomial curve. | `scale_polynomial(v,dmin,dmax,rmin,rmax,e)` | domain + range + exponent | `scale_polynomial(5,0,10,0,100,2) → 25` |
| sin | Returns sine of angle. | `sin(angle)` | angle — radians | `sin(1.571) → 0.999999` |
| sqrt | Square root. | `sqrt(value)` | value — number | `sqrt(9) → 3` |
| tan | Tangent of angle. | `tan(angle)` | angle — radians | `tan(1.0) → 1.5574` |
