# coolest-background
easy to create coolest background using flat-surface-shader

#  really easy to use! You only need 3 minute to learn how to use

  - # step1
  Introducing  the script to your page
```sh
   <script src="[???]/coolestBackground.min.js"></script>
```
  If you are using es6 ,webpack ,react or etc. ,just add one sentence in the script
```sh
  export {coolestBackground}
```
- # step2 
  set css like this:
```sh
  #example{
  position:absoulte;
  width:100%;
  height:100%;
  }
```
  and in your script
```sh
<script>coolestBackground(document.getElementById('example'))</script>
```
- # step3 -open the html and enjoy the amazing effect
#  API
- size and postion are setted by css
```sh
coolestBackground(dom[,config])
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
