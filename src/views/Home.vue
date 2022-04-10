<template>
  <section class="Home">
    
    <div class="front-img">
      <img src="../assets/img/sad_rassvet_oochertaniya_55026_1280x720.jpg" alt="trees">
    </div>

    <div class="title-info">
      <div class="title">
        <div>
          <h1>Мы <span class="active">поможем</span> привести вашу дачу в порядок</h1>
          <p>сайт тимуровцев для помощи <span class="active">дачникам</span></p>
        </div>
      </div>

      <div class="info">
        <div class="info-btn">
          <div>
            <p>Устав от городской суеты, все больше людей в наше время стремится уединиться в уютном загородном доме, где можно будет расслабиться и забыть обо всех проблемах.</p>

            <div class="btn">
              узнать больше
              <img src="../assets/icons/arrow.png" alt="arrow">
            </div>
          </div>
        </div>

        <div class="back-img">
          <img src="../assets/img/doma_sklon_tuman_167050_1280x720.jpg" alt="house">
        </div>
      </div>
    </div>

    <div class="search-network">
      <div class="img-search">
        <img src="../assets/icons/icons8-поиск-480.png" alt="search">
      </div>

      <div class="network">
        <h3>instagram</h3>
        <h3>twitter</h3>
        <h3>FACEBOOK</h3>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  name: 'Home',

  components: {
  }
}
</script>

<style scoped>
section.Home{
  width: 100%; height: 100vh;
  display: flex;
  /* background: center / cover no-repeat url('../assets/img/photo_2022-04-06_17-21-09.jpg'); */
  overflow: hidden;
}

section.Home > .front-img{
  width: 34%; height: 100%;
  position: relative;
  overflow: hidden;
  /* opacity: 50%; */
}

section.Home > .front-img img{
  width: 100%; height: 100%;
  object-fit: cover;
  object-position: center center;
}

section.Home > .title-info{
  width: 59%; height: 100%;
  background: #fff;
  /* opacity: 50%; */
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

section.Home > .title-info .title{
  width: 100%; height: 55%;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

section.Home > .title-info .title > div{
  width: 60%;
  margin-top: 3rem;
  margin-left: 4rem;
  /* border: 2px solid #333; */
}

section.Home > .title-info .title > div h1{
  text-align: end;
  font-size: 3.3rem;
  font-weight: 400;
  margin-bottom: 1.5rem;
  line-height: 1.1;
  color: var(--titleColor);
}

section.Home > .title-info .title > div h1 span.active{
  color: var(--titleActiveColor);
}

section.Home > .title-info .title > div p{
  text-align: end;
  font-size: 1.4rem;
  font-weight: 400;
  transform: translate(2rem);
  color: var(--dbTitleColor);
}

section.Home > .title-info .title > div p span.active{
  color: var(--dbTitleActiveColor);
}

section.Home > .title-info .info{
  width: 100%; height: 45%;
}

section.Home > .title-info .info{
  display: flex;
  background: var(--bgColorInfo);
}

section.Home > .title-info .info .info-btn{
  width: 50%; height: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

section.Home > .title-info .info .info-btn > div{
  width: 70%; height: auto;
  text-align: start;
  margin-left: 5rem;
  margin-top: 3rem;
  color: #fff;
}

section.Home > .title-info .info .info-btn > div p{
  font-size: 1.3rem;
  text-transform: uppercase;
}

section.Home > .title-info .info .info-btn > div .btn{
  font-size: 1.1rem;
  margin-top: 1.5rem;
  text-transform: uppercase;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  cursor: pointer;
  transition: text-shadow 0.25s;
}

section.Home > .title-info .info .info-btn > div .btn:hover{
  text-shadow: 0 0 7px #fff;
}

section.Home > .title-info .info .info-btn > div .btn *{
  margin-left: 2rem;
}

section.Home > .title-info .info .back-img{
  width: 50%; height: 100%;
  position: relative;
  overflow: hidden;
}

section.Home > .title-info .info .back-img img{
  width: 100%; height: 100%;
  object-fit: cover;
  object-position: 0 0;
} 

section.Home > .search-network{
  width: 7%; height: 100%;
  background: var(--bgColorNetwork);
  /* opacity: 50%; */
}

section.Home > .search-network > .img-search{
  width: 100%; height: 11%;
  background: var(--bgColorInfo);
  display: flex;
  align-items: center;
  justify-content: center;
}

section.Home > .search-network > .img-search img{
  width: 2rem; height: 2rem;
}

section.Home > .search-network > .network{
  width: 100%; height: 89%;
  padding: 9rem 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}

section.Home > .search-network > .network h3{
  color: #fff;
  transition: 0.5s;
  text-transform: uppercase;
  transform: rotate(90deg);
  cursor: pointer;
  font-weight: 400;
}

section.Home > .search-network > .network h3:hover{
  text-shadow: 0 0 3px #fff;
}

@media (max-width: 1720px){
  section.Home > .title-info .title > div h1{
    font-size: 3rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1.2rem;
  }

  section.Home > .title-info .info .info-btn > div p{
    font-size: 1.1rem;
  }

  section.Home > .title-info .info .info-btn > div .btn{
    font-size: 1rem;
  }
}

@media (max-width: 1559px){
  section.Home > .title-info .title > div{
    width: 65%;
  }
}

@media (max-width: 1440px){
  section.Home > .title-info .title > div h1{
    font-size: 2.7rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1rem;
  }

  section.Home > .title-info .info .info-btn > div{
    margin-left: 3rem;
  }

  section.Home > .title-info .info .info-btn > div p{
    font-size: 1rem;
  }

  section.Home > .title-info .info .info-btn > div .btn{
    font-size: 0.9rem;
  }

  section.Home > .title-info .info .back-img img{
    object-fit: cover;
    object-position: 0 0;
  }
}

@media (max-width: 1287px){
  section.Home > .front-img{
    width: 48%;
  }

  section.Home > .title-info{
    width: 52%;
  }

  section.Home > .title-info .title > div{
    margin-left: 0rem;
    width: 90%;
  }

  section.Home > .title-info .title > div h1{
    font-size: 2.7rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1rem;
  }

  section.Home > .title-info .info .info-btn > div{
    margin-left: 5rem;
    margin-top: 0.4rem;
  }

  section.Home > .title-info .info .info-btn > div p{
    font-size: 1.4rem;
  }

  section.Home > .search-network{
    display: none;
  }

  section.Home > .title-info .info .info-btn{
    width: 100%;
  }

  section.Home > .title-info .info .info-btn > div .btn{
    font-size: 1.2rem;
  }

  section.Home > .title-info .info .back-img{
    display: none;
  }
}

@media (max-width: 1110px){
  section.Home > .front-img{
    display: none;
  }

  section.Home > .title-info{
    width: 100%;
  }

  section.Home > .title-info .info .info-btn > div{
    width: 62%;
  }

  section.Home > .title-info .title{
    width: 70%;
  }

  section.Home > .title-info .title > div h1{
    font-size: 3.1rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1.3rem;
  }
}

@media (max-width: 670px){
  section.Home > .title-info .title{
    width: 95%;
  }

  section.Home > .title-info .title > div p{
    font-size: 1rem;
  }
}

@media (max-height: 910px){
  section.Home > .title-info .title > div h1{
    font-size: 2.7rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1.1rem;
  }

  section.Home > .title-info .info .info-btn > div p{
    font-size: 1rem;
  }

  section.Home > .title-info .info .info-btn > div .btn{
    font-size: 0.9rem;
  }

  section.Home > .title-info .info .info-btn > div{
    margin-left: 3rem;
    margin-top: 1rem;
  }

  section.Home > .search-network > .network h3{
    font-size: 1rem;
  }
}

@media (max-height: 800px){
  section.Home > .title-info .title > div{
    width: 45%;
    margin-left: 8rem;
  }

  section.Home > .title-info .title > div h1{
    font-size: 2.2rem;
  }

  section.Home > .title-info .title > div p{
    font-size: 1rem;
  }

  section.Home > .title-info .info .info-btn > div p{
    font-size: 0.8rem;
  }

  section.Home > .title-info .info .info-btn > div .btn{
    font-size: 0.7rem;
  }

  section.Home > .title-info .info .info-btn > div .btn img{
    width: 1.8rem; height: 0.8rem;
  }

  section.Home > .title-info .info .info-btn > div{
    margin-left: 3rem;
    margin-top: 1rem;
    width: 55%;
  }

  section.Home > .search-network > .network h3{
    font-size: 1rem;
  }

  section.Home > .search-network > .img-search img{
    width: 1.3rem;
    height: 1.3rem;
  }

  section.Home > .search-network > .network h3{
    font-size: 0.8rem;
  }
}
</style>