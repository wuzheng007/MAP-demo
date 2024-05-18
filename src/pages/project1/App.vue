<template>
  <h1>页面：project1</h1>
  <div class="area nav">
    <div class="nav-item">
      <h3>切换路由</h3>
      <router-link to="/"><button>首页</button></router-link>
      <router-link to="/about"><button>关于</button></router-link>
    </div>
    <div class="nav-item">
      <h3>切换页面</h3>
      <a href="/project1"><button>project1</button></a>
      <a href="/"><button>main</button></a>
      <a href="/project2"><button>project2</button></a>
    </div>
  </div>
  <div class="area">
    <h3>router-view显示</h3>
    <router-view></router-view>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.nav-item {
  h3 {
    text-align: center;
    margin-bottom: 10px;
  }
}
</style>