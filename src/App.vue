<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />

    <div class="bg-info clearfix">
      <button type="button" class="btn btn-secondary float-left">
        Example Button floated left
      </button>
      <button type="button" class="btn btn-secondary float-right">
        Example Button floated right
      </button>
    </div>
    <h2 class="h1 p-2 mb-3 border">Icons</h2>

    <b-button size="sm" class="mb-2">
      <b-icon icon="gear-fill" aria-hidden="true"></b-icon> Settings
    </b-button>

    <div class="h3 mb-0">
      <b-icon-arrow-up variant="warning" />
      <b-icon-exclamation-triangle-fill variant="warning" />
      <b-icon icon="arrow-up" variant="danger" class="h1 mb-2" />
      <b-icon icon="exclamation-triangle" variant="danger" />
    </div>
    <b-iconstack font-scale="3" animation="cylon">
      <b-icon
        stacked
        icon="camera"
        animation="throb"
        variant="info"
        scale="0.75"
      ></b-icon>
      <b-icon
        stacked
        icon="slash-circle"
        animation="spin-reverse"
        variant="danger"
      ></b-icon>
    </b-iconstack>

    <div class="embed-responsive embed-responsive-16by9">
      <iframe
        class="embed-responsive-item"
        src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0"
        allowfullscreen
      ></iframe>
    </div>

    <div class="p-4 row mx-md-n5">
      <div class="col px-md-5">
        <div class="p-3 border bg-light">Custom column padding</div>
      </div>
      <div class="col px-md-5">
        <div class="p-3 border bg-light">Custom column padding</div>
      </div>
    </div>

    
    
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 60px 0;
  background-color: var(--body-color);
}

.float-left {
  float: left;
}
.float-right {
  float: right;
}
</style>
