<!DOCTYPE html>
<html>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}
</style>
<body>

<!-- Header -->
<div class="header">
  <h1>Nature <3 </h1>
  <p>Nature is the vast, beautiful, and essential physical world, encompassing everything from majestic mountains and oceans to tiny plants and animals, providing us with life's necessities like clean air, water, and food, yet it faces threats from human activities, making preservation through sustainable practices like planting trees and reducing waste crucial for future generations.</p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="https://img.freepik.com/free-photo/cascade-boat-clean-china-natural-rural_1417-1356.jpg" style="width:100%">
    <img src="https://rukminim2.flixcart.com/image/480/480/jjbqufk0/poster/t/v/x/large-vlnature00093a-natural-scene-of-beautiful-bird-vinyl-original-imaeh9vdy7kzxzdy.jpeg?q=90" style="width:100%">
    <img src="https://www.shutterstock.com/image-photo/sun-sets-behind-mountain-ranges-600nw-2479236003.jpg" style="width:100%">
    <img src="https://images.pexels.com/photos/70365/forest-sunbeams-trees-sunlight-70365.jpeg" style="width:100%">
    <img src="https://static.toiimg.com/thumb/104555810/104555810.jpg?height=746&width=420&resizemode=76&imgsize=200956" style="width:100%">
    <img src="https://thumbs.dreamstime.com/b/natural-scenery-765671.jpg" style="width:100%">
    <img src="https://media.istockphoto.com/id/1550071750/photo/green-tea-tree-leaves-camellia-sinensis-in-organic-farm-sunlight-fresh-young-tender-bud.jpg?s=612x612&w=0&k=20&c=RC_xD5DY5qPH_hpqeOY1g1pM6bJgGJSssWYjVIvvoLw=" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTY9tdE8JWZs6u8sOqLO35MPAjPhaqBLk2XNA&s" style="width:100%">
    <img src="https://img.freepik.com/premium-photo/morning-serenity-dewkissed-moss-sprouts-soft-natural-light_1067911-7823.jpg?semt=ais_hybrid&w=740&q=80" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ35P-MlfiDJzb8al_A7QygscvlwrUZuhuxmA&s" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWJ1gjg9S7DPZY-bcRMbC_KtrTgarBJ4l31A&s" style="width:100%">
    <img src="https://elements-resized.envatousercontent.com/envato-dam-assets-production/038824ed-b308-4b8a-9f3b-ce8f4e37e655/ece7c232-e0e4-4751-a4ce-411118eae4d3.jpg?w=500&cf_fit=scale-down&mark-alpha=18&mark=https%3A%2F%2Felements-assets.envato.com%2Fstatic%2Fwatermark4.png&q=85&format=auto&s=8572ec698f125e982e06ee06b317c1d71afadc295d0bdadf428f07515ff58fad" style="width:100%">
    <img src="/w3images/underwater.jpg" style="width:100%">
  </div>  
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTW-2-uOUYueLz3rvWs_ywEaSzBx8N_aOF9Hg&s" style="width:100%">
    <img src="https://natureworldwide.in/wp-content/uploads/2023/10/Nohkalikai-Fall-1024x1281.jpg" style="width:100%">
    <img src="https://lh3.googleusercontent.com/proxy/IgNNlsWDNaFQeJedlbyEZ3wLZQHcQmD0f7JD93JaiJW5ETADH7F_zpR9-zCARk0BqwTTXblLt81-ihHAPPDD4UkKghj6aQj3LAMqJe26F7_sbI7A5pSjkEM3" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_gyxQLXLQym8wYb_vglBlYKo2HJDKtmivCg&s" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTA8XBbbMcwHaveGP82ezfKInylc-6xqKB4WQ&s" style="width:100%">
    <img src="https://media.istockphoto.com/id/2181735944/photo/natural-mountains-landscapes.jpg?s=612x612&w=0&k=20&c=4EZdF1438jegkW3U8h0TG4JaPO_cpMMBY-MouwLlyf4=" style="width:100%">
    <img src="https://thumbs.dreamstime.com/b/lakeside-nature-walk-way-photograph-showing-beautiful-curving-wooden-board-walkway-tropical-park-natural-style-34127577.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="https://timesofagriculture.in/wp-content/uploads/2023/10/1600x800_Natural_farming-1024x576.jpg" style="width:100%">
    <img src="https://earth.org/wp-content/uploads/2021/10/rsz_sk_rahaman_hossain_1-min.jpg" style="width:100%">
    <img src="https://images.picxy.com/cache/2020/7/4/8c653acb413d2c91753fcbb28b367a2d.jpg" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTOLo7KenKYh70Sv765tDfRrBlmFukl-C1WZA&s" style="width:100%">
    <img src="https://static.toiimg.com/thumb/msid-110769473,width-748,height-499,resizemode=4,imgsize-244708/.jpg" style="width:100%">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZVJaAe6dwQV8o1RN5PNniHDREBoMDfH2OXw&s" style="width:100%">
  </div>
</div>

</body>
</html>


