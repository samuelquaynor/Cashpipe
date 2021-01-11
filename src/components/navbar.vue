<template>
    <div class="navbar-top" style="background-color: #26A9E0">
        <div class="container">
            <div class="row p-2 justify-vertical">
                <div class="col-12 col-md-6 col-lg-6 text-center text-md-left">
                    <p class="text-white m-0">
                        Any Question Contact us: +233 5060 500 50
                    </p>
                </div>
                <div class="col-12 col-md-6 col-lg-6 text-center text-md-right">
                    <p class="text-white m-0" v-blink>Coming Soon!</p>
                </div>
            </div>
        </div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-light" id="nav" style="background-color: #E7EFFF">
            <div class="container">
                <a href="index.html" class="navbar-brand logo">
                    <img src="../assets/static/images/CashpipeLogoVertical.png" alt="Logo" style="width: 200px">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#service">Service</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
</template>
<script>
export default {
  directives: {
    blink: {
      beforeMount(el) {
        let isVisible = true;
        setInterval(() => {
          isVisible = !isVisible;
          el.style.visibility = isVisible ? 'visible' : 'hidden';
        }, 500);
      }
    }
  }
}
</script>

<style scoped>
</style>