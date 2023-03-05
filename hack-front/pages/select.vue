<template>
  <div
    class="d-flex align-items-center justify-content-center flex-column"
    style="height: 85vh"
  >
    <div class="row mb-5">
      <div class="col">
        <h1>Выберите подходящую для Вас стажировку</h1>
      </div>
    </div>

    <div class="row my-2">
      <div class="col">
        <div class="card" @click="goto('/detail')">
          <img src="/img/frontend.png" alt="" class="card-img-top" />
          <div class="card-body text-center">Разработчик Front-end</div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/analytic.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Аналитик данных</div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/sysadmin.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Системный администратор</div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/sysadmin.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Разработчик баз данных</div>
          </div>
        </div>
      </div>
    </div>
    <div class="row my-2">
      <div class="col">
        <div class="card" @click="goto('/detail')">
          <img src="/img/frontend.png" alt="" class="card-img-top" />
          <div class="card-body text-center">Разработчик Java/Kotlin</div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/analytic.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Разработчик под мобильные платформы</div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/sysadmin.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Разработчик PHP</div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <div class="card" @click="goto('/detail')">
            <img src="/img/sysadmin.png" alt="" class="card-img-top" />
            <div class="card-body text-center">Системный аналитик</div>
          </div>
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
