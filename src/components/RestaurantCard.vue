<template>
  <div class="restaurant--card">
    <div class="restaurant--image">

    </div>
    <div class="restaurant--information">
      <div class="top">
        <p class="name">
          Subway
        </p>
        <p class="note">
          <span>
            4.5
          </span>
        </p>
      </div>
      <p class="time">
          20-30mn
        </p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .restaurant--card{
        width: 32%;
        height: 30vh;
    }

    p{
      margin: 0;
    }
    .restaurant--image{
      background-image: url('../assets/image/bgRestaurant1.webp');
      height: 70%;
      background-size: cover;
      background-position: center;
      width: auto;
    }
    .restaurant--information{
      margin: 10px 0px;
      .top{
        display: flex;
        align-items: center;
        justify-content: space-between;
        .note{
          background-color: #eee;
          display: flex;
          height: 30px;
          width: 30px;
          justify-content: center;
          align-items: center;
          font-size: 0.8rem;
          border-radius: 50% ;
        }
      }
    }
</style>