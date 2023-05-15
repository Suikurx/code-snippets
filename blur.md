## Blur

Creates Blur on an Image

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blur</title>
</head>
<body>
    <div class="furekisu">
        <div class="blur" style="background-image:url('./assets/disc.jpeg')"></div>
    </div>
                    
<style>
    ::-webkit-scrollbar{width:13px;}
    ::-webkit-scrollbar-track{background:#1a1a22;}
    ::-webkit-scrollbar-thumb{background:#33333e;width:11px;}
    ::-webkit-scrollbar-thumb:hover{background:#272730;}
    .furekisu{
      width:96vw;
      height:auto;
      margin:4vw auto;
      display:flex;
      flex-direction:row;
      flex-wrap:wrap;
      justify-content:space-evenly;
      gap:4vw;
    }
    .blur{
        image-rendering:auto;
        background-size:cover;
        width:60vw;
        height:60vw;
        max-width:360px;
        max-height:360px;
        filter:brightness(83%)contrast(163%)blur(23px)grayscale(20%);
        transform:scale(0.97);
        transition:filter 0.6s ease, transform 0.6s ease;
      }
      .blur:hover{
        filter:brightness(100%)contrast(100%)blur(0)grayscale(0%);
        transform:scale(1);
        transition:filter 1.2s cubic-bezier(.18,1.71,.78,.49), transform 1s cubic-bezier(.18,1.71,.78,.49);
      }
</style>
</body>
</html>
```

Source: https://psychicnewborn.neocities.org/insect/