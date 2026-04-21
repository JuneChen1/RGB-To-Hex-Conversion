# Codewars- RGB To Hex Conversion (Javascript)

```
function rgb(r, g, b) {
  const colorCode = [r, g, b].map(num => {
    if (num > 255){
      num = 255;
    } else if (num < 0) {
      num = 0;
    }

    return num.toString(16).toUpperCase().padStart(2, '0');
  })
  
  return colorCode.join('');
}
```

[KATA](https://www.codewars.com/kata/513e08acc600c94f01000001/javascript)
<br>

[解題](https://medium.com/@juneee/codewars-rgb-to-hex-conversion-javascript-9dd34ec2cda1)
