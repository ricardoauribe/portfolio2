<template>
  <header>
    <nav class="navbar fixed-top">
      <div class="flex-grow-1 text-left">
        <div class="title">Ricardo Uribe</div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
    name: 'AppHeader'
}
</script>

<style>
    .navbar {
      background-color: #000;
      padding-left: 15px;
      padding-top: 8px;
      padding-right: 15px;
      padding-bottom: 4px;
      margin-top: 0px;
      align-items: right;
    }
    .title {
        color: #C6EFFF;
        font-weight: 600;
        font-size: larger;
        margin: 0px;
        padding-bottom: 0px;
        margin-bottom: 0px;
    }
</style>