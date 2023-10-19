<template>
  <div class="header-notif">
    <div class="header-container-title" style="justify-content: normal; margin-bottom: 30px">
      <i class="bi bi-arrow-left" style="margin-right: 20px; font-size: 16px; font-weight: 900; cursor: pointer" @click="$router.push('/')"></i>
      <div class="header-title">Notification</div>
    </div>
  </div>
  <div style="height: 670px; overflow-x: auto; width: 420px; padding-left: 30px; margin-left: -33px;">
    <div class="card-notif" style="background-color: #9fc0e7;">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-coin-64.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-success">
            <i class="bi bi-check" style="color: white; font-size: 22px; margin-left: -3px; margin-top: -10px"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Reimbursment</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">paid</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-coin-64.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-danger">
            <i class="bi bi-x"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Reimbursment</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">rejected</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif" style="background-color: #9fc0e7;">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-coin-64.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-primary">
            <i class="bi bi-arrow-right"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Reimbursment</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">processed</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-capsule-78.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-success">
            <i class="bi bi-check" style="color: white; font-size: 22px; margin-left: -3px; margin-top: -10px"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Sickness</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">approved</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-capsule-78.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-danger">
            <i class="bi bi-x"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Sickness</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">rejected</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif" style="background-color: #9fc0e7;">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-capsule-78.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-primary">
            <i class="bi bi-arrow-right"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Sickness</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">reviewed</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-alarm-clock-48.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-success">
            <i class="bi bi-check" style="color: white; font-size: 22px; margin-left: -3px; margin-top: -10px"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Overtime</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">approved</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-alarm-clock-48.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-danger">
            <i class="bi bi-x"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Overtime</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">rejected</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
    <div class="card-notif" style="background-color: #9fc0e7;">
      <div style="display: flex">
        <div class="card-notif-content">
          <div class="container-logo-notif">
            <img src="@/assets/icons/icons8-alarm-clock-48.png" width="40" height="40" style="margin-left: auto; margin-right: auto">
          </div>
          <div class="status-logo-primary">
            <i class="bi bi-arrow-right"></i>
          </div>
        </div>
        <div style="display: inline-grid">
          <div style="display: flex; justify-content: space-between">
            <div class="title-notif">Overtime</div>
            <div style="margin-right: 15px" class="time-notif">Today</div>
          </div>
          <div class="desc-notif"><span style="font-weight: bold">reviewed</span> ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis corporis dolorem et incidunt iusto qui ratione tempore tenetur voluptates. A, beatae consectetur eligendi eos explicabo illum ipsum maiores quod repudiandae?</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
</script>