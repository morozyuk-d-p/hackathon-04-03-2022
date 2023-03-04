<template>
  <div
    class="d-flex align-items-center justify-content-center flex-column"
    style="height: 60vh"
  >
    <div class="row mt-3">
      <div class="col">
        <h3>Вопрос 1</h3>
        <p>В чём здесь ошибка?</p>
        <p class="p-3" style="background-color: black">
          <code style="color: greenyellow">
            var em = new events.EventEmitter(); // Обработчик<br />
            myEmit.on('event_name', function() { // Создание события<br />
            // Вывод информации после обработки события<br />
            console.log("Это событие сработало!");<br />
            });
          </code>
        </p>
      </div>
      <div class="col">
        <form @submit="goto('/quiz-result')" action="/quiz-result">
          <h4>Варианты ответа:</h4>

          <div class="m-2">
            <input type="radio" name="choice" id="first" class="me-3" />
            <label for="first">Вместо myEmit необходимо прописать em</label>
          </div>
          <div class="m-2">
            <input type="radio" name="choice" id="second" class="me-3" />
            <label for="second">Здесь нет ошибок</label>
          </div>
          <div class="m-2">
            <input type="radio" name="choice" id="third" class="me-3" />
            <label for="third"
              >Функция обязательно должна принимать параметр</label
            >
          </div>
          <div class="m-2">
            <input type="radio" name="choice" id="fourth" class="me-3" />
            <label for="fourth">"event_name" - такого события нет</label>
          </div>
          <div class="d-flex">
            <button class="btn text-white" style="background: #50b848">
              Далее
            </button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script setup>
function goto(path) {
  window.location.replace(path);
}
</script>
