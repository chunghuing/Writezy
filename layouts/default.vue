<template>
  <!-- 導航 -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Writezy</a>
      <!-- 收合按鈕 -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- 導覽選項 -->
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <NuxtLink class="nav-link" aria-current="page" to="./">動態牆 </NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="./Register"> 註冊 </NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="./Login"> 登入 </NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- 主要內容 -->
  <div class="container my-5">
    <main>
      <slot />
    </main>
  </div>
</template>

<script setup></script>
