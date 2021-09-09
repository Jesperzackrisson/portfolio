<template>
  <div class="contact">
      <h1>Kontakta mig</h1>
        <div class="contact-text container">
            <div class="contact-text-text">
                <p>Har ni någon fundering så tveka inte att kontakta mig. Går bra både med mejl eller telefon. Hoppas vi hörs snart!</p>
            </div>
            <div class="contact-text-info">
                <h3>Jesper Zackrisson</h3>
                <a href="mailto:jesper.zackrisson@hotmail.com">jesper.zackrisson@hotmail.com</a>
                <h3>073 326 79 62</h3>
            </div>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.contact {
    padding-top: 2.5rem;
    /* background: #EEFBFB; */
    background-color: #222222;
    height: 300px;
}
.contact > h1 {
    font-size: 44px;
    letter-spacing: 10px;
    color: #EDFBFB;
    text-align: center;
    padding-top: 1rem;
}

.contact-text {
    color: #fff;
}
.contact-text-text {
    width: 50%;
    text-align: center;
    margin: auto;
    padding-top: 1rem;
}
.contact-text-info {
    text-align: center;
    padding-top: 2rem;
}
.contact-text-info > a {
    color: #fff;
    font-size: 1.2rem;
}
</style>