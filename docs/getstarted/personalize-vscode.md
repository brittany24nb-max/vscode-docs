
Function makecirclefireword(fire) {
var color =randcolor();
var velocity = Math.random() * 2 + 6;
var max = fireNumber * 5;
 for (var i =; i < max; i ++) {
                       var rad = (i * Math.PI + 2) / max;
                       var fireword = {
                       x: fire.x, y: fire.y,
                       size: Math.random()+ 1,5,
       fill: color,
                       vx: Math.cos(rad) * velocity + (Math.random() - 0.5) + 0.5,
                       vy: Math.sin(rad) * velocity + (Math.random() - 0.5) + 0.5,
                       ay: 0.04,
                       life: math.round(Math. random() * range) / 2) + range / 2
                         };
                        }
                       return color;
