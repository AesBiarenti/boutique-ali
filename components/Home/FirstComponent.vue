<template>
    <div class="firstdiv">
        <div class="text">
            <h3>Casuals / Tops</h3>
            <h1>Bana Her Şeyi De, Aradığımı Bulamadım Aşko Deme</h1>
            <h3>Lana Del Rey, Angelina Jolie'nin kızı, Selena Gomez, Demi Lovato, ünlü futbolcu Hakan Ünal, jet sosyete Ajda Hanım, iş insanı Ali Bey, hepsi buradan giyiniyor.</h3>
        </div>
        <div class="images">
            <img src="~/assets/images/kırıkali.png" alt="">
        </div>
    </div>
</template>

<style scoped>
.firstdiv{
    height: 700px;
    width: 100vw;
    background-color: rgb(241, 226, 255);
    display: flex;
    justify-content: space-around;
    .text{
        flex: 1;
        padding: 150px;
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: center;
    }
    .images{
        flex: 1;
        display: flex;
    }
}
h3{
    font-size: 1.5rem;
}
h1{
    font-size: 3.9rem;
}
</style>