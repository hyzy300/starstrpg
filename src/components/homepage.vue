<template>
  <body>
    <span></span>
    <div id="app">
      <div class="home">
        <div class="header">
          <div class="first"><slot class="first"></slot></div>
          <div class="second"><slot class="second"></slot></div>
          <div class="third"><slot class="third"></slot></div>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name
};
</script>

<style>
  .header {
    display: flex;
    line-height: 64px;
  }
  .first,.second{
    width: 60px;
    background-color: darkblue;
  }

</style>