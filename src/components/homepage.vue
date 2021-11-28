<template>
  <head>
    <meta charset="UTF-8" />
    <meta
      name="description"
      content="Free Web Providing Auxiliary Tools For TRPG"
    />
    <meta name="keywords" content="TRPG,跑团" />
  </head>
  <body>
    <span></span>
    <div id="app">
      <div class="home">
        <div class="header">
          <div class=""><slot></slot></div>
          <div class=""><slot></slot></div>
          <div><slot></slot></div>
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
    line-height: 80px;
  }
</style>