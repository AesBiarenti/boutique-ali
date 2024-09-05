<template>
    <div class="thirddiv">
      <div class="title">
        <center>
          <h1>İndirimli Ürünler</h1>
          <hr />
        </center>
      </div>
      <div class="products">
        <div class="resim1">
          <div class="favorite-button">
            <Button class="button" variant="outline" size="icon">❤️</Button>
          </div>
          <img src="~/assets/images/images.jpg" alt="" />
          <h2>Kahverengi Bluz</h2>
          <div class="price">
            <h2>135 TL</h2>
            <h2 class="line">335 TL</h2>
            <Button>Sepete Ekle</Button>
          </div>
        </div>
        <div class="resim1">
          <div class="favorite-button">
            <Button class="button" variant="outline" size="icon">❤️</Button>
          </div>
          <img src="~/assets/images/images.jpg" alt="" />
          <h2>Kahverengi Bluz</h2>
          <div class="price">
            <h2>135 TL</h2>
            <h2 class="line">335 TL</h2>
            <Button>Sepete Ekle</Button>
          </div>
        </div>
        <div class="resim1">
          <div class="favorite-button">
            <Button class="button" variant="outline" size="icon">❤️</Button>
          </div>
          <img src="~/assets/images/images.jpg" alt="" />
          <h2>Kahverengi Bluz</h2>
          <div class="price">
            <h2>135 TL</h2>
            <h2 class="line">335 TL</h2>
            <Button>Sepete Ekle</Button>
          </div>
        </div>
        <div class="resim1">
          <div class="favorite-button">
            <Button class="button" variant="outline" size="icon">❤️</Button>
          </div>
          <img src="~/assets/images/images.jpg" alt="" />
          <h2>Kahverengi Bluz</h2>
          <div class="price">
            <h2>135 TL</h2>
            <h2 class="line">335 TL</h2>
            <Button>Sepete Ekle</Button>
          </div>
        </div>
        <!-- Repeat for other products -->
      </div>
    </div>
  </template>
  
  <style scoped>
  .thirddiv {
    height: 800px;
    display: flex;
    flex-direction: column;
    justify-content: start;
    margin: 50px 200px;
  }
  
  .products {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 120px;
  }
  
  h1 {
    font-size: 3em;
  }
  
  h2 {
    font-size: 1.3em;
    font-weight: 600;
    padding: 10px;
  }
  
  img {
    width: 100%;
    height: 75%;
  }
  
  .resim1 {
    background-color: rgb(243, 243, 243);
    height: 400px;
    width: 25vw;
    margin: 10px 15px;
    display: flex;
    flex-direction: column;
    align-items: start;
    position: relative; /* Added to position the button relative to this container */
  }
  
  .favorite-button {
    position: absolute;
    top: 10px; /* Adjust this value to change the vertical position */
    right: 10px; /* Adjust this value to change the horizontal position */
    z-index: 10; /* Ensures the button is on top of the image */
  }
  
  .price {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
  }
  
  .line {
    text-decoration: line-through;
  }
  </style>
  