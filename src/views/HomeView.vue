<template>
  <div class="home">
    <div class="heading">
      <h1>DRIFT PARADISE</h1>
      <h3>
        Уникальный дрифт проект в мире Multi Theft Auto. Наш первый сервер
        открылся в 2016 году
      </h3>
    </div>

    <div class="content">
      <div class="stats">
        <div class="stats__item">
          <div class="stats_title">Всего игроков</div>
          <div class="stats_value">50 000</div>
        </div>
        <div class="stats__item">
          <div class="stats_title">Игроков онлайн</div>
          <div class="stats_value">1 200</div>
        </div>
        <div class="stats__item">
          <div class="stats_title">Всего серверов</div>
          <div class="stats_value">14</div>
        </div>
      </div>

      <div class="image">
        <img src="../assets/home-car.png" alt="" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  overflow: hidden;
  width: 100%;
}

.heading {
  max-width: 70%;
}

.content {
  display: flex;
  margin-top: 4rem;
  align-items: center;
}

h1 {
  font-weight: 700;
  font-size: 4.2vw;
  color: #ff004d;
}

h3 {
  font-size: 2.3vw;
  font-weight: 500;
}

.stats_title {
  font-size: 1.2vw;
}

.stats_value {
  color: #ff004d;
  font-size: 2vw;
  font-weight: 700;
}

.image {
  object-fit: cover;
  overflow: hidden;
}
</style>
