# 3x3GaussianBlur

Changing the values like this makes it a Box Blur
```
    var k1 = [[1, 1, 1],
		         [1, 1, 1],
		          [1, 1, 1]];

    var devide = 9
```
Without this code the algorithem will blur the entire image
```
        // Blur only 1 color 
          
        if (px[mc] !== 243 
            || px[mc+1] !== 83 
            || px[mc+2] !== 37){
                continue;
            }
```
