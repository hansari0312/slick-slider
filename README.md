
<style>@keyframes slidy {
0% { left: 0%; }
20% { left: 0%; }
25% { left: -100%; }
45% { left: -100%; }
50% { left: -200%; }
70% { left: -200%; }
75% { left: -300%; }
95% { left: -300%; }
100% { left: -400%; }
}

body { margin: 0; } 
div#slider { overflow: hidden; }
div#slider figure img { width: 20%; float: left; }
div#slider figure { 
  position: relative;
  width: 500%;
  margin: 0;
  left: 0;
  text-align: left;
  font-size: 0;
  animation: 30s slidy infinite; 
}

</style>


<base href="https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/">
<div id="slider">
<figure>
<img src="austin-fireworks.jpg" alt>
<img src="taj-mahal_copy.jpg" alt>
<img src="ibiza.jpg" alt>
<img src="ankor-wat.jpg" alt>
<img src="austin-fireworks.jpg" alt>
</figure>
</div>
