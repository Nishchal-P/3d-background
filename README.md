# [demo1]  [demo2]  [demo3]
[demo1]:<https://a49666.github.io/3d-background/example/example1.html>
[demo2]:<https://a49666.github.io/3d-background/example/example2.html>
[demo3]:<https://a49666.github.io/3d-background/example/example3.html>



css 
```sh
  #example{
  position:absoulte;
  width:100%;
  height:100%;
  }
```

#  API
- size and postion are setted by css
```sh
config: {
    mode:{
        display: ['canvas'|'svg'|'webgl'], 
        move:[boolean]   //in the center or follow your mouse
    },
    MESH :{          
        width: [number],
        height: [number],
        depth: [number],
        segments: [number],
        slices: [number],
        xRange: [number],
        yRange: [number],
        zRange: [number],
        ambient: [color],
        diffuse: [color],
        speed: [number],
    },
    LIGHT : {
        count:  [number],
        xyScalar: [number],
        zOffset:  [number],
        ambient: [color],
        diffuse: [color],
        speed:  [number],
        gravity:  [number],
        dampening: [number],
        minLimit:  [number],
        maxLimit: [number],
        minDistance: [number],
        maxDistance: [number],
        autopilot: [boolean]  // the light auto fly anywhere
        draw: [boolean]   //   show the small circle around your mouse
    }
}
```
#  EXAPMLE
- Here are 3 examples in the files to tell you how to set configs and set 4 backgounds in one page.

#   OTHER
- The project is based on [flat-surface-shader] ,majority parameters can be tried in the http://matthew.wagerfield.com/flat-surface-shader/ 

[flat-surface-shader]: <https://github.com/wagerfield/flat-surface-shader>
