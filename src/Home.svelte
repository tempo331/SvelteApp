<script>
</script>
<body class="body">
    <h1 class="article">Фотографии загородного клуба</h1>
    <hr class="green-line">
    <h2>Шале</h2>
    <div class="container">
      <img
        class="img"
        src="http://hday33.ru/img/220318/220318_14.jpg"
        alt="sfsdfd"
      />
      <img
        class="img"
        src="http://hday33.ru/img/220617/DSC_0300%D1%87%D1%81%D1%87.jpg"
        alt="sfsdfd"
      />
      <img
        class="img"
        src="http://hday33.ru/img/220318/220318_3.jpg"
        alt="sfsdfsdfd"
      />
      <img
        class="img"
        src="http://hday33.ru/img/220318/220318_4.jpg"
        alt="dfsfsdfd"
      />
    </div>
    <h2>Дом-сауна</h2>
      <div class="container">
        <img
          class="img"
          src="http://hday33.ru/img/0U6A6110.jpg"
          alt="sfsdfsdfd"
        />
        <img
          class="img"
          src="http://hday33.ru/img/220318/230318_2.JPG"
          alt="sfsdfsdfd"
        />
        <img
          class="img"
          src="http://hday33.ru/img/0U6A6099.jpg"
          alt="dfsfsdfd"
        />
        <img
          class="img"
          src="http://hday33.ru/img/220318/230318_1.jpg"
          alt="sfsdfd"
        />
      </div>
</body>

<style>

.article {
display: flex;
justify-content: center;
}
.green-line {
  width: 300px;
  color: #00a49d;
  border-color: #00a49d;
  margin-top: 50px;
}
h2 {
  display: flex;
  justify-content: center;
  margin-top: 50px;
  margin-bottom: 0;
}
.container {
  /* margin-top: 20px; */
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: wrap;
}
.img {
  padding-top: 30px;
  width: 450px;
  height: 280px;
}

    @media screen and (max-width: 768px) {
    div {
        padding-top: 20px;
        display: flex;
        flex-direction: column;
        align-items: center;
  }
}

@media screen and (max-width: 768px) {
    img {
        padding-top: 20px;
  }
}
    
</style>