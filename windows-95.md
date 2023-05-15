## Windows 95 Window

Creates A Windows 95 Looking Window on Your Webpage


```
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
			<meta name="viewport" content="width=device-width, initial-scale=1.0">
				<title>Windows 95</title>
                <body>
                    <div class="win95 window">
                        <div class="win95 titleBar">Windows 95</div>
                        <div class="win95 Box" style="height: 500px;width: 420px">
                        <div style="text-align: center;"> </div>
                    </div>
                    <style>

/* Background and overall layout */

html {
  background: rgb(236, 237, 219);
  font-family: monospace;
  font-size: 9pt;
  background-image: url("/img/y2k_water_tile.png");
  background-size: 1024px;
  image-rendering: optimizespeed;
  image-rendering: pixelated;
}

.column {
    image-rendering: initial;
}

.columnsWrapper {
    display: flex;
    width: fit-content;
    margin: auto;
}

hr {
  width:100%
}


/* win95 specific stying */

.win95.window{
  --win95Color: #ccc;
  --win95Gradient: linear-gradient(90deg, #048, rgb(28, 0, 238));
  padding:4px;
  margin:24px;
  background: var(--win95Color);
  width: fit-content;
  box-shadow:
     inset -1px -1px 0px 0px black,
     inset -2px -2px 0px 0px #0008,
     inset 1px 1px 0px 0px var(--win95Color),
     inset 2px 2px 0px 0px #FFFA,
     8px 8px 0 0 #0004;
}

.win95.Box{
  border: white 1px solid;
  border-color: black #FFFA #FFFA black;
  height: 250px;
  width: 300px;
  display: flex;
}

.win95.titleBar {
  height: 16px;
  background: var(--win95Gradient);
  color: white;
  text-shadow: 1px 1px black;
}

.win95 textarea {
  align-self: stretch;
  color: grey;
}

</style>	
        </div>
			</body>
        </head>
        </html>
```

Source: https://mileshouse.neocities.org/wip/japanese-app