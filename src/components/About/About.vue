<template>
  <div class="about">
      <h1>Vem är jag?</h1>
        <div class="about-image">
            <img src="../../assets/ProfilePicture1.png">
        </div>
        <div class="about-text">
          <h1>Jesper Zackrisson</h1>
          <p>Hej! Jesper heter jag och är en 24 årig kille som nu letat efter min första LIA - praktik, på distans eller i närheten av Västerås/Stockholm. Jag studerar mitt andra år som Frontend-utvecklare och hoppas därmed på att hitta en spännande och lärorik praktikplats där jag kan få chansen att visa mina praktiska kunskaper, likaväl som att få lära mig av er.</p>
          <br>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.about {
    height: 228px;
    /* background: #1A262F; */
    /* background: #203647; */
    /* background: #4DA8DA; */
    background: #EEFBFB;
    margin: auto;
    /* margin-top: 0rem; */
    margin-bottom: 3rem;
}
.about > h1 {
    color: #222222;
    font-size: 44px;
    letter-spacing: 10px;
    text-align: center;
    padding-top: 3rem;
}
.about-image {
    width: 200px;
    height: 200px;
    background: #FFFFFF;
    border-radius: 50%;
    margin: auto;
    margin-top: 3rem;
    /* border: 1px solid #333333; */
}
.about-image > img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
}
.about-image > h1 {
    text-align: center;
    position: relative;
    top: 40%;
    color: #1d976c;
}
.about-text {
    margin: auto;
    color: #EEFBFB;
}
.about-text > h1 {
    text-align: center;
    padding-top: 2rem;
    word-spacing: 8px;
    font-family: 'Big Shoulders Stencil Display', cursive;
}
.about-text > p {
    width: 900px;
    text-align: center;
    margin: auto;
    padding-top: 1.5rem;
    font-family: 'Courier New', Courier, monospace;
    line-height: 1.5rem;
}
/* @media screen and (max-width: 1440px) {
.about {
    width: 1425px;
    height: 238px;
    background: #333333;
    margin: auto;
    margin-top: 2rem;
}
} */
</style>