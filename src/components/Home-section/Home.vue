<template>

  <div class="home-page">
      <h1>Välkommen</h1>
      <div class="home d-flex">
          <div class="home-text">
            <h3>Jag heter Jesper,</h3>
            <h3>Frontend utvecklare,</h3>
            <h3>Student</h3>
          </div>
      </div>

      <i class="fas fa-arrow-circle-down"></i>
      <!-- <div class="home-text">
          <h1>Välkommen till min portfolio</h1>
          <h3>Frontend-utvecklare</h3>
          <h3>Student</h3>
          <button><a href="mailto:jesper.zackrisson@hotmail.com">KONTAKTA MIG </a></button>
      </div> -->
      <!-- <div class="home-picture"></div> -->
      
  </div>
</template>

<script>
export default {

}
</script>

<style>

.home-page {
    justify-content: space-around;
    width: 100%;
    margin: auto;
    padding-top: 5rem;
    height: 100vh;
    /* background: linear-gradient(to right, #e44d26, #f16529); */
}
.home-page > h1 {
    text-align: center;
    color: #EDFBFB;
    opacity: .1;
    font-size: 12rem;
    padding-top: 4rem;
}
.home-picture {
    border-radius: 0 0 0 100%;
    width: 900px;
    height: 900px;
    background-color: #67DFE0;
    position: relative;
    left: 600px;
    bottom: 600px;
    z-index: 0;
}

.home {
    color: #EDFBFB;
    margin-left: 15rem;
    justify-content: space-between;
    width: 75%;
}
.home-text > h1 {
    font-size: 30px;
    font-family: 'Courier New', Courier, monospace;
}
.home-text > h3 {
    font-size: 2rem;
    font-family: 'Courier New', Courier, monospace;
}
.home-text > button {
    border: none;
    border-radius: 15px;
    background-color: #EDFBFB;
    color: #222222;
    padding: 12px 20px;
    margin-top: 1rem;
    cursor: pointer;
    opacity: 0.7;
}
button:hover {
    opacity: 1;
}

a {
    text-decoration: none;
    color: #222222;
}

.fas {
    color: #EDFBFB;
    font-size: 2.5rem;
    position: absolute;
    top: 90%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>