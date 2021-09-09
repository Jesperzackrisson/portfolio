<template>
  <div class="project-page">
      <div class="projects">
          <div class="project-text">
              <h1>Mina projekt</h1>
          </div>
        <div class="d-flex project1" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/JOOD_mac.png" class="img1">
            </div>
            <div class="project-info flex-child">
                <h3>Jood</h3>
                <p>Detta projekt gjordes i samband med kursen HTML och CSS - 40 yhp, som varade i 8 veckor. Projektet gick ut på att genom en design från läraren, använda både html och css för att få till en sån lik hemsida som möjligt.  </p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button @click="getGitUrl1" class="git">Git</button>
                </div>
            </div>
        </div>
        <div class="d-flex project2" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/DC_mac.png" class="img2">
            </div>
            <div class="project-info flex-child">
                <h3>DentialClinic</h3>
                <p>Detta projekt gjordes i samband med kursen HTML och CSS - 40 yhp, som varade i 8 veckor. Projektet gick ut på att genom en design från läraren, använda både html och css för att få till en sån lik hemsida som möjligt.</p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>
        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/manage_mac.png" class="img3">
            </div>
            <div class="project-info flex-child">
                <h3>Manage</h3>
                <p>Detta projekt gjorde jag utanför skolan. Jag fick tag på projektet hos frontendmentor.io, där det finns projekt för alla möjliga nivåer för personer i min sits. Under detta projekt användes bara html och css.</p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>
            
        <hr>

        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/JS1_1_mac.png" class="img4">
            </div>
            <div class="project-info flex-child">
                <h3>Registrera användare</h3>
                <p>Detta projekt gjordes under kursen Javascript 1. Projektet gick ut på att lära sig javascript genom att göra ett valideringsformulär, där det var möjligt att skapa och sedan logga in en användare. </p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>
        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/JS1_2_mac.png" class="img5">
            </div>
            <div class="project-info flex-child">
                <h3>TODO</h3>
                <p>Detta projekt gjordes under kursen Javascript 1 och var den andra uppgiften. Projektet gick ut på att man skulle göra en sån kallad TODO applikation, där de var möjligt för användaren att skapa en todo som senare skulle bli utskriven på skärmen. </p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>

        <hr>

        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/portfolio_mac.png" class="img6">
            </div>
            <div class="project-info flex-child">
                <h3>Portfolio</h3>
                <p>Min Portfolio är något som jag gjort utanför skolan. Idén med den var att få kunna visa upp mina kunskaper som jag hittils har fått under skoltiden. Portfolio är byggd i Vuejs, och valet att just välja VueJs på detta projekt var för att fördjupa sig i just VueJs.</p>
                <div class="buttons">
                    <button class="git">Git</button>
                </div>
            </div>
        </div>
        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/vue-shop2-mac.png" class="img7">
            </div>
            <div class="project-info flex-child">
                <h3>Webshop - Vue</h3>
                <p>Denna webshop gjordes i Javascript 2 kursen, där fokuset låg på VueJs. Webshopen är byggd så att man kan se dem listade produkterna som kommer från de dokumentorienterade databasprogrammet mongodb. Projektet var väldigt nyttigt där man fick sitta med VueJs och Vuex för att kunna kommunicera med databasen. </p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>

        <hr>

        <div class="d-flex project3" v-scrollAnimation>
            <div class="laptop flex-child">
                <img src="../../assets/laptop.png" class="img">
                <img src="../../assets/react2_shop_mac.png" class="img8">
            </div>
            <div class="project-info flex-child">
                <h3>Webshop - React</h3>
                <p>Denna webshop gjordes i Javascript 3 kursen, där fokuset låg på React. Webshopen är byggd så att man kan se dem listade produkterna som kommer från de dokumentorienterade databasprogrammet mongodb. Projektet var väldigt nyttigt där man fick sitta med react för att kunna kommunicera med databasen.</p>
                <div class="buttons">
                    <!-- <button class="url">Url</button> -->
                    <button class="git">Git</button>
                </div>
            </div>
        </div>

      </div>
  </div>
</template>

<script>
export default {
  methods: {
      getGitUrl1() {
          window.open('https://github.com/Jesperzackrisson/Inlamingsuppgift2')
      },
      getGitUrl2() {
          window.open('https://github.com/Jesperzackrisson/Inlamningsuppgift-1')
      },
      getGitUrl3() {
          window.open('https://github.com/Jesperzackrisson/ManageLandingPage')
      },
      getGitUrl4() {
          window.open('https://github.com/Jesperzackrisson/JS_inl-mningsuppgift_1')
      },
      getGitUrl5() {
          window.open('https://github.com/Jesperzackrisson/JS_Inl-mningsuppgift_2')
      },
      getGitUrl6() {
          window.open('https://github.com/Jesperzackrisson/Inlamingsuppgift2')
      },
      getGitUrl7() {
          window.open('https://github.com/Jesperzackrisson/javascript2')
      },
      getGitUrl8() {
          window.open('https://github.com/Jesperzackrisson/Inlamningsuppgift1')
      },
  }
}
</script>

<style >

hr {
    border: 1px solid #222222;
    margin-bottom: 5rem;
    opacity: .5;
}
.flex-child {
    flex: 1;
    margin: auto;
}
.project1 {
    padding-bottom: 5rem;
    padding-top: 5rem;
}
.project2 {
    padding-bottom: 5rem;
}
.project3 {
    padding-bottom: 5rem;
}
.img {
    width: 70%;
}
.img1 {
    width: 25%;
    position: absolute;
    left: 25.5%;
    top: 46.9%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img2 {
    width: 25%;
    position: absolute;
    left: 25.5%;
    top: 34.5%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img3 {
    width: 25%;
    height: 66%;
    position: absolute;
    left: 25.5%;
    top: 34.7%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img4 {
    width: 25%;
    position: absolute;
    left: 25.5%;
    top: 35.0%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img5 {
    width: 25%;
    position: absolute;
    left: 25.5%;
    top: 34.6%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img6 {
    width: 25%;
    height: 66%;
    position: absolute;
    left: 25.5%;
    top: 35%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img7 {
    width: 25%;
    height: 66%;
    position: absolute;
    left: 25.5%;
    top: 37%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.img8 {
    width: 25%;
    height: 66%;
    position: absolute;
    left: 25.5%;
    top: 35%;
    transform: translate(-50%, -50%);
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
}
.project-info > h3 {
    padding-bottom: 1.5rem;
    font-size: 2rem;
    font-family: 'Big Shoulders Stencil Display', cursive;
    width: 50%;
}
.project-info > p {
    padding-bottom: 1.5rem;
    font-family: 'Courier New', Courier, monospace;
    width: 60%;
}
.buttons {
    margin-left: 2rem;
}
.buttons > button {
    padding: 10px 40px;
    border-radius: 20px;
    margin: auto .5rem;
    font-size: 1rem;
    cursor: pointer;
    float: left;
}
.url {
    background-color: #222222;
    color: #EDFBFB;
    border: 1px solid #222222;
}
.git {
    background-color: #EDFBFB;
}
.git:hover {
    background-color: #222222;
    color: #EDFBFB;
    border: 1px solid #222222;
}
.project-page {
    margin: auto;
    padding-top: 24rem;
    position: relative;
    z-index: 1;
}
.projects {
    background: #EEFBFB;
    height: 3200px;
    text-align: center;
    animation: project-load 300ms ease-in;
}

@keyframes project-load {
    
    0% {
        transform: translateX(-20px);
        opacity: 0;
    }

    100% {
        transform: translateX(0px);
        opacity: 1;
    } 
}

.project-text {
    text-align: center;
    color: #222222;
}
.project-text > h1 {
    font-size: 44px;
    letter-spacing: 10px;
    padding-top: 1rem;
}


.before-enter {
    opacity: 0;
    transform: translateX(-100px);
    transition: all 1.5s ease-out;
}
.enter {
    opacity: 1;
    transform: translateX(0);
}
</style>