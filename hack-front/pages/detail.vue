<template>
  <div class="mt-5">
    <div class="row" style="font-size: x-large">
      <div class="col">
        <p>
          <strong>Мы предлагаем:</strong>
        </p>
      </div>
      <div class="col">
        <ul>
          <li>Гибкий график</li>
          <li>Официальное оформление</li>
          <li>Сертификат о прохождении стажировки</li>
          <li>
            Возможность принять участие в разработке уникальных технологий
          </li>
          <li>Атмосферу стартапа</li>
        </ul>
      </div>
    </div>
    <div class="row" style="font-size: x-large">
      <div class="col">
        <p>
          <strong> Требования: </strong>
        </p>
      </div>
      <div class="col">
        <ul>
          <li>Владение стэком веб-технологий PHP/JS/HTML/CSS</li>
          <li>Знание общего SQL</li>
          <li>Желательно наличие опыта работы с фреймворками</li>
        </ul>
      </div>
    </div>
    <div class="row mt-5">
      <div class="col">
        <div class="d-flex">
          <button
            class="btn text-white flex-fill"
            style="background: #50b848; font-size: x-large"
            @click="goto('/quiz')"
          >
            Проверить свой уровень подготовки
          </button>
        </div>
      </div>
      <div class="col">
        <div class="d-flex">
          <button
            class="btn text-white flex-fill"
            style="background: #50b848; font-size: x-large"
            @click="goto('/anketa')"
          >
            Заполнить анкеты
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
function goto(path) {
  window.location.replace(path);
}
</script>
