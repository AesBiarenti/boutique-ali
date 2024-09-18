<template>
  <div class="shoppage">
    <aside>
      <div class="baslik">
        <h1>Filter</h1>
      </div>
      <div class="filters">
        <CustomCheckBox class="checkboxes" label="Pantolon"></CustomCheckBox>
        <CustomCheckBox class="checkboxes" label="Ceket"></CustomCheckBox>
        <CustomCheckBox class="checkboxes" label="Sweet"></CustomCheckBox>
        <CustomCheckBox class="checkboxes" label="Şort"></CustomCheckBox>
        <CustomCheckBox class="checkboxes" label="Elbise"></CustomCheckBox>
      </div>
    </aside>
    <div class="products">
      <div class="product">
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
  </div>
</template>

<style scoped>
.shoppage{
    display: flex;
}
aside {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 300px;
  background-color: aliceblue;
  height: calc(100vh - 100px);
  padding: 20px;
}
h1 {
  font-size: 1.5em;
  font-weight: 500;
}
.filters {
  margin-top: 50px;
}
.checkboxes {
  margin: 10px;
}
.products{
    width: calc(100vw - 300px);
    height: calc(100vh - 100px);
}
.product {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 120px;
}
</style>
