<template>
  <footer>
    <div class="help">
      <h2>Help</h2>
      <h3>Bizle İletişime Geç</h3>
      <h3>Ya da Geçme</h3>
      <h3>Sen Bilirsin</h3>
    </div>
    <div class="company">
      <h2>Company</h2>
      <h3>Hakkımızda</h3>
      <h3>Bloglar</h3>
    </div>
    <div class="info">
      <h2>More İnfo</h2>
      <h3>Gizlilik Politikamız</h3>
      <h3>Ticaret Politikamız</h3>
    </div>
    <div class="contact">
      <h2>Contact</h2>
      <h3>boutiqueali@cimeil.com</h3>
    </div>
  </footer>
</template>

<style scoped>
footer {
  height: 400px;
  width: 100vw;
  background-color: black;
  display: flex;
  flex-direction: row;
  padding: 50px;
  align-items: start;
  justify-content: center;
  color: white;
}
.help,
.company,
.info,
.contact {
  height: 100%;
  margin: 10px;
  flex: 1;
  text-align: center;
}
h2 {
  font-size: 2em;
  font-weight: 500;
}
h3 {
  font-size: 1.5em;
  font-weight: 500;
  color: rgb(226, 226, 226);
  margin: 10px 0;
}
</style>
