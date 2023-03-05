<template>
  <div class="container">
    <header class="mt-5 ms-5">
      <div class="row">
        <div class="col-auto">
          <a href="/">
            <img src="/img/logo.png" alt="Логотип" />
          </a>
        </div>
        <div class="col" style="background-color: #50b848">
          <div class="row">
            <div class="col-auto">
              <div class="d-flex">
                <input
                  type="text"
                  placeholder="Поиск стажировки"
                  class="mt-2 mb-1"
                  style="background: transparent; border: 0px"
                />
                <button class="btn text-white" @click="goto('/detail')">
                  <i class="bi bi-search"></i>
                </button>
              </div>
            </div>
            <div class="col">
              <div class="d-flex justify-content-end">
                <ul class="nav">
                  <li class="nav-item">
                    <a href="" class="nav-link text-white">О нас</a>
                  </li>
                  <li class="nav-item">
                    <a href="" class="nav-link text-white">Контакты</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
    <slot />
  </div>
</template>

<script setup>
function goto(path) {
  window.location.replace(path);
}
</script>

<style>
input::placeholder {
  color: white;
}
</style>
