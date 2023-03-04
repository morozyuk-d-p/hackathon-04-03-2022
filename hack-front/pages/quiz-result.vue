<template>
  <div
    class="d-flex align-items-center justify-content-center flex-column"
    style="height: 85vh"
  >
    <h3>Результаты тестирования</h3>
    <div class="row m-5">
      <div class="col">
        <div
          class="d-flex align-items-center justify-content-center flex-column"
          style="font-size: larger; height: 100%"
        >
          <p>Правильных ответов: 10</p>
          <p>Ошибок: 5</p>
          <p>Итоговый результат: 75%</p>
        </div>
      </div>
      <div class="col">
        <img src="/img/graph.png" alt="" />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <p class="h5 text-center">
          Ваш уровень является достаточным для прохожения стажировки.
        </p>
        <p class="h5 text-center">Дополнительное обучение не требуется.</p>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div
          class="mt-3 d-flex align-items-center justify-content-center flex-column"
        >
          <button
            class="btn text-white"
            style="background: #50b848; font-size: x-large"
            @click="goto('/anketa')"
          >
            Заполнить анкету
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
