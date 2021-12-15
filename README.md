# Runner map
A map generator for your my_runner.

### The generator is currently accessible at https://runner-map.tk

## How to use ?

Each time you use the map generator, you must import your configuration file which will adapt the workspace to your needs.

The configuration file is a JSON which is used like this:

```json
{
    "width": "<default map width>",
    "height": "<default map height>",
    "mode": "<map storage mode>",
    "sprites": {
        "<id1>":"<hex color1>",
        "<id2>":"<hex color2>",
        //...
    }
}
```

Then you can draw by choosing your sprites in the toolbox.

`Shift + Click` will draw a full horizontal line.

Clicking on an existing color will replace it with air.

You can now export your map by clicking on export button.

Copy all the output text and store it as you want on your computer.

You can import your map to work on it whenever you want.

## What is map storage mode ?
You can choose between "vertical" and "horizontal"

A same map will be stored like this in vertical:
```
1    
1    
12   
122  
1222 
1    
1    
1222 
122  
12   
1    
1    
1    
11   
121  
11   
1    
1    
1    
1    
```
And like this in horizontal :
```
                    
    2  2            
   22  22     1     
  222  222   121    
11111111111111111111
```
