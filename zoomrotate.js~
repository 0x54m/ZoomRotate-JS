/* For Zoom-Rotate behavior.

By Samet Kohen
*/
<script type="text/javascript"> var rotation = 0;
var scale = 1;
function gesture(event) { event.target.innerHTML = "Rotation: " +
Math.round((event.rotation+rotation)*100)/100
+ " Scale: " + Math.round((event.scale*scale)*100)/100; event.target.style.webkitTransform = "rotate(" + (event.rotation+rotation)%360
+ "deg)" + " scale(" + event.scale*scale + ")";
function gestureend(event) {
rotation = event.rotation+rotation;
scale = event.scale*scale; }
</script>
</head>
<body>
<div ongesturechange="gesture(event)" ongestureend="gestureend(event)" style="background-color:silver; width: 100%; height: 300px">
</div>
