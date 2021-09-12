<template>
  <div class="about">

    <h2>{{ title }}</h2>

    <div class="row">

      <div class="avatar-container">

        <img src="./myProfile.jpg" alt="" class="avatar">

        <div class="icons-container">
          <img src="./react.svg" alt="">
          <img src="./nodejs.svg" alt="">
          <img src="./mongo.svg" alt="">
        </div>

      </div>

      <div class="text-container">

        <div class="card-header">

          <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
            <circle cx="32" cy="32" r="30" fill="#ed4c5c"/>
          </svg>

          <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
            <circle cx="32" cy="32" r="30" fill="#FDCB58"/>
          </svg>

          <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
            <circle cx="32" cy="32" r="30" fill="#78B159"/>
          </svg>
          
        </div>

        <div class="card-body">

          <h3>Hi :)</h3>

          <p>👋 I'm HOANG Minh Chau. FULLSTACK JAVASCRIPT WEB DEVELOPER to become. After experiences in the civil engineering industry, I am now moving into the IT development world. Link between my initial training and my future professional: my appetite for technology and the design of new products. I'm now student at Coding Bootcamp La Capsule - Fullstack JavaScript web and mobile development. 💜</p>

        </div>

      </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'About',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  .about {
    display: flex;
    flex-direction: column;
    align-items: center;

    h2 {
      padding-top: 60px;
      font-size: 30px;
    }

    .row {
      display: flex;
      align-items: center;
      justify-content: space-around;

      .avatar-container {
        margin: 55px 75px 30px 75px;
        padding: 15px 15px 30px 15px;
        display: flex;
        flex-direction: column;
        box-shadow: 0 4px 6px gray;

        .avatar {
          height: 250px;
          width: auto;
        }

        .icons-container {
          display: flex;
          justify-content: space-around;
          margin-top: 18px;

          img {
            width: 40px;
            height: auto;
          }
        }

      }

      .text-container {
        border: 1px solid rgba(0,0,0,.125);
        flex-basis: 50%;

        .card-header {
          padding: 7.5px 12.5px;
          background-color: rgba(0,0,0,.03);
          border-bottom: 1px solid rgba(0,0,0,.125);
          display: flex;
          gap: 0.5rem;

          svg {
            width: 10px;
            height: 10px;
          }

        }

        .card-body {
          margin: 0 10px;
          padding: 12.5px;
          
          p {
            font-weight: lighter;
          }

        }

      }

    }

  }

</style>
