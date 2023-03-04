<template>
  <div
    class="d-flex align-items-center justify-content-center"
    style="height: 85vh"
  >
    <div class="row">
      <div class="col">
        <img src="/img/hero.png" alt="" />
      </div>
      <div class="col">
        <div
          class="d-flex align-items-center justify-content-center flex-column h-100"
        >
          <p class="h1 text-center">
            Присоединяйся к оплачиваемой программе стажировок для молодых
            специалистов!
          </p>
          <div class="d-flex justify-content-center mt-4">
            <button
              onclick="window.location.replace('/select')"
              class="btn text-white"
              style="background: #50b848; font-size: x-large"
            >
              Выбрать стажировку
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
