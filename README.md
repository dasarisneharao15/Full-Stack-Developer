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
  <h1>South Indian cuisine </h1>
  <p>South Indian cuisine, spanning the states of Tamil Nadu, Kerala, Karnataka, Andhra Pradesh, and Telangana, is a vibrant, predominantly plant-based culinary tradition deeply rooted in rice, coconut, and tamarind. Known for its bold, tangy, and often fiery flavor profiles, it relies heavily on fermentation techniques to create nutritious staples like idli (steamed rice cakes) and dosa (crispy rice crepes), which are often served with sambar (a savory lentil broth) and various coconut-based chutneys. While rice acts as the staple foundation, the cuisine varies by region—ranging from the coconut-rich seafood dishes of coastal Kerala to the intensely spicy, chili-forward preparations of Andhra Pradesh. Often served on traditional banana leaves, this cuisine utilizes aromatic curry leaves, mustard seeds, and tempering to produce light, easily digestible, and healthy meals. </p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="https://www.culturalindia.net/iliimages/South%20Indian%20Food_1.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQsStjdUOkbFCwkmqN3-Ju-39trgmQyoyedpA&s" style="width:100%">
  </div>  
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGPpT7WXDSKLNvRxfZqzOuH_zeCRwc0OJEMg&s" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2C6I7dtJjjOmfGQYiYXR2ULaO84QJUiAoGQ&s" style="width:100%">
  </div>
</div>

</body>
</html>

