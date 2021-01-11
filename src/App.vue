<template>
  <navbar/>
  <index/>
</template>

<script>
import navbar from './components/navbar.vue'
import index from './components/index.vue'

export default {
  name: 'App',
  components: {
    navbar,
    index,
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;400;500;600;700;800;900&display=swap');

:root{
    --ff-primary: 'Poppins', san-serif;
    --ff-secondary: 'Montserrat', monospace;

    --ff-reg: 200;
    --ff-bold: 600;

    --clr-light: #fff;
    --clr-blue: #26A9E0;
    --clr-dark: #2E5161;
    --clr-black: #000000;

    --fs-h1: 2.5rem;
    --fs-h2: 2rem;
    --fs-h3: 1.25rem;
    --fs-body: 1rem;

}

/*-----@media(){}-----*/

*{
    transition: all .4s ease-in-out;
    font-family: var(--ff-primary);
    font-weight: 400;
}

p{
    color: rgba(105,108,113,1);
    line-height: 1.9;
}

html {
    scroll-behavior: smooth!important;
}

ul{
    list-style-type: none;
}

h2{
    font-size: var(--fs-h2)!important;
    font-weight: 500;
}

h3{
    font-size: 20px!important;
    line-height: 42px!important;
    font-weight: 600!important;
    color: rgba(49,50,51,1)!important;
}

a{
    color: var(--clr-blue);
    text-decoration: none!important;
}

.nav-section{
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}

.navbar a{
    color: var(--clr-blue);
    text-transform: uppercase;
    font-size: 16px;
    font-weight: 500;
}

.navbar-toggler{
    color: transparent!important;
    border: none!important;
}

.login-signup .sign-up{
    color: var(--clr-light);
}

.main-content{
    padding-top: 100px;
    height: 700px;
}

.main-content h5{
    font-size: 100%;
    margin-bottom: 20px;
    padding-bottom: 30px;
}

.main-content h2{
    font-size: 36px;
    line-height: 1.4em;
}

.main-content p{
    font-size: 100%;
    line-height: 1.8em;
    font-weight: 500;
    padding-bottom: 20px;
}

.form-control{
    border-radius: 20px!important;
    padding: 14px 4%!important;
    color: #666!important;
    font-size: 16px!important;
}

.main-content form .btn{
    width: 100%!important;
    border-radius: 20px;
}

.logo{
    width: 100%;
}

.navbar-brand{
    width: 150px;
}

.navbar a:hover{
    color: var(--clr-blue);
    font-weight: 600;
}

.navbar-collapse{
    flex-grow: 0!important;
}

.navbar .container{
    padding: 15px 0;
}

.main-content .btn{
    background-color: var(--clr-blue);
    border: none;
}

.main-content .btn:hover{
    background-color: var(--clr-blue);
}

.text-3 .fas{
    font-size: 1rem!important;
}

.featured-box .fas{
    color: var(--clr-blue);
    font-weight: 900;
    font-size: 40px;
    margin-bottom: 20px;
}

.section{
    padding: 100px 0;
}

.section-two, .section-four{
    background: #26a8e01a;
}

.btn-link{
    color: var(--clr-blue)!important;
}

.text-20{
    font-weight: 500px!important;
    font-size: 5.75rem!important;
}

.btn-primary{
    background-color: var(--clr-blue)!important;
    border-color: transparent!important;
}

footer{
    padding-top: 50px;
}

.media{
    display: inline-block;
    justify-content: space-between;
}

.media a{
    color: var(--clr-dark)!important;
}

.media li{
    display: inline-block;
    margin: 0 10px;
}

footer ul{
    padding-left: 0;
    font-size: 14px;
    font-weight: 200;
}

footer li{
    margin: 15px 0;
}

footer p{
    font-size: 14px;
    font-weight: 200;
    line-height: 2em;
    color: #000
}

footer .fas, .far{
    float: left;
    padding-right: 10px;
    font-size: 20px;
}

.footer-image{
    width: 70%;
}

footer .logo{
    padding-bottom: 30px;
    width: 150px;
}

</style>
