<template>
  <div class="home">
    <section class="presentacion">
      <div class="nombre-cargo">
        <h1>Hi, I'm Daniel</h1>
        <h2 class="full_stack">Full Stack Developer</h2>
      </div>
      <figure class="foto_presentacion"></figure>
    </section>
    <section class="content">
      <div class="about">
        <a>Hi, I'm Daniel. Nice to meet you</a>
        <br />
        <br />
        <p>
          Since beginning my journey as a full stack developer nearly
          <b>2</b> years ago, I've done remote work for agencies, and
          collaborated with talented people to create digital products for both
          business and consumer use.<br /><br />I'm quietly confident, naturally
          curious, and perpetually working on improving my chops one design
          problem at a time.
        </p>
      </div>
      <div class="technologies">
        <h1>My Power Skills</h1>
        <figure>
          <a href="https://www.python.org/" target="_blank">
            <img src="../assets/img/logo-python.png" alt="" />
          </a>
          <a href="https://www.javascript.com/" target="_blank">
          <img src="../assets/img/logo-js.png" alt="" />
          </a>
        
        </figure>
      </div>
      <div class="technologies">
        <!-- <h1>FRAWEWORKS</h1> -->
        <figure>
          <a target="_blank" href="https://www.djangoproject.com/">
          <img src="../assets/img/logo-django.png" alt="" />
          </a>
          <a target="_blank" href="https://vuejs.org/">
          <img src="../assets/img/logo-vue.png" alt="" />
          </a>
          <a target="_blank" href="https://quasar.dev/">
          <img src="../assets/img/logo-quasar.png" alt="" />
          </a>
        </figure>
      </div>
      <div class="technologies">
        <!-- <h1>VERSION CONTROL</h1> -->
        <figure>
          <a target="_blank" href="https://github.com/">
          <img src="../assets/img/logo-git.png" alt="" />
          </a>
          <a target="_blank" href="https://bitbucket.org/product/">
          <img src="../assets/img/logo-bitbucket.png" alt="" />
          </a>
          <a href="https://www.microsoft.com/es-co/windows/">
          <img src="../assets/img/logo-windows.png" alt="" />
          </a>
          <a href="https://ubuntu.com/download">
          <img src="../assets/img/logo-ubuntu.png" alt="" />
          </a>
        </figure>
      </div>
      
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  data() {
    return {
      datetime: new Date(),
    };
  },
};
</script>
<style scoped>
@import url("../assets/css/home.css");
@import url("https://fonts.googleapis.com/css2?family=Neonderthaw&family=PT+Sans:ital,wght@0,700;1,700&display=swap");
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@800&display=swap');
</style>
