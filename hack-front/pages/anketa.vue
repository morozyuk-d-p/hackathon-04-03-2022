<template>
  <form class="my-5 p-4" action="" style="background: #50b84866">
    <div class="m-2">
      <label for="fio" class="form-label">ФИО</label>
      <input
        type="text"
        id="fio"
        class="form-control"
        placeholder="Иванов Иван Иванович"
      />
    </div>
    <div class="m-2">
      <label for="birthday" class="form-label">Дата рождения</label>
      <input
        type="date"
        id="birthday"
        class="form-control"
        placeholder="22.03.2000"
      />
    </div>
    <div class="m-2">
      <label for="phone" class="form-label">Телефон</label>
      <input
        type="phone"
        id="phone"
        class="form-control"
        placeholder="+7-908-576-84-52"
      />
    </div>
    <div class="m-2">
      <label for="email" class="form-label">Телефон</label>
      <input
        type="email"
        id="email"
        class="form-control"
        placeholder="ivanov@mail.com"
      />
    </div>
    <div class="m-2">
      <label for="major" class="form-label">Специальность</label>
      <input
        type="text"
        id="major"
        class="form-control"
        placeholder="Информационные технологии"
      />
    </div>
    <div class="m-2">
      <label for="year" class="form-label">Курс</label>
      <input type="number" id="year" class="form-control" placeholder="4" />
    </div>
    <div class="m-2">
      <label for="achievements" class="form-label">Ваши достижения</label>
      <textarea
        name="achievements"
        id="achievements"
        cols="30"
        rows="10"
        class="form-control"
      ></textarea>
    </div>
    <div class="m-2">
      <label for="cv" class="form-label">Ваше резюме</label>
      <input type="file" name="cv" id="cv" class="form-control" />
    </div>
    <div class="form-check m-2">
      <input
        type="checkbox"
        name="agreement"
        class="form-check-input"
        id="agreement"
      />
      <label for="agreement" class="form-check-label"
        >Я даю согласие на обработку персональных данных</label
      >
      <div class="mt-3 d-flex align-items-center justify-content-center flex-column">
        <button class="btn text-white" style="background: #50b848; font-size: larger;">
          Далее
        </button>
      </div>
    </div>
  </form>
</template>
