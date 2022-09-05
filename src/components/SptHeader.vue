<template>
      <header>
            <div class="logo">
                  <h1>SPT</h1>
            </div>
            <div class="status">
                  <h3>Ocupado<br>
                        <span class="atendente"> Rafael Menezes</span>
                  </h3>
            </div>
            <div class="usuario">

                  <i class="fa-regular fa-circle-user"></i>

            </div>

      </header>
</template>

<script>
export default {
      name:'SptHeader'

}
</script>

<style scoped>
header {
      position: relative;
      top: 0;
      left: 0;
      display: flex;
      width: 100%;
      min-height: 50px;
      justify-content: space-between;
      align-items: center;
      background: #e4ebf0;
}

.logo,
.title,
.usuario {
      width: 33%;
}

.logo {
      
      padding: 0 30px;
      text-align: left;
}

.status {
      text-align: center;
}

.status h3 {
      padding: 5px;
}

.atendente {
      font-size: 0.7em;
}

.usuario {
      text-align: right;
      font-size: 2.8em;
}
.usuario i {
      margin-right: 25px;
}
</style>