<template>
  <div class="wrap">
    <div class="wrap-content">
        <div class="wrap-list">
            <canvas class="stat-model" id="stat-model">
            </canvas>
        </div>
        <div class="wrap-list">
            <a class="list">
                성장 과정.
            </a>
            <a class="list">
                Portfolio.
            </a>
            <a class="list">
                Contact.
            </a>
        </div>
    </div>
</div>
</template>

<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<style lang="scss">
.wrap {
    width: 100%;
    height: 100vh;
    background-color: #353535;
    display: flex;
    align-items: center;
    justify-content: center;
    .wrap-content {
        width: 90%;
        height: 90%;
        display: flex;
        border: 1px solid wheat;  
        .content {
            width: 100%;
            height: 100%;
            border: 1px solid red;
        }
        .wrap-list {
            width: 100%;
            height: 100%;
            align-items: center;
            .list {
                width: 90%;
                height: 10vh;
                background-color: whitesmoke;
                border: 5px solid black;
                border-radius: 10px;
                margin: 0 auto;
                margin-top: 50px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .list:hover {
                cursor: pointer;
            }
        }
    }
}
</style>
