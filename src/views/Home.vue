<template>
  <div class="home">
    <section class="presentacion">
      <div class="nombre-cargo">
        <h1>Hi, I'm Daniel</h1>
        <h2 class="full_stack">Full Stack Developer</h2>
        <!-- <figure>
            <img src="../assets/img/logo-git.png" alt="git">
            <img src="../assets/img/logo-instagram.png" alt="instagram">
          </figure> -->
        <div class="terminal">
          <div class="btn-close"></div>
          <div class="btn-minimize"></div>
          <div class="btn-maximize"></div>
          <div class="terminal-title">📂 My Own Terminal</div>
          <div class="terminal-content">
            <p class="frase1">
              Last login {{ this.datetime.toString().split("GMT")[0] }} on
              ttys000
              <br />
              DevFullStack:~ cat my_passion.txt
              <br />
              <br />
              💻 I design and code beautifully simple things, and I love what I
              do 🍹
              <br />
              <br />
              Follow me on:
              <br />
              &nbsp;👬&nbsp;linkedin:
              <a href="https://www.linkedin.com/in/daniel-ibarra-python/"
                >www.linkedin.com/in/daniel-ibarra-python/</a
              >
              <br />
              &nbsp;🐱&nbsp;github:
              <a href="https://github.com/programador-negro"
                >github.com/programador-negro</a
              >
              <br />
              <br />
              DevFullStack:~<b>_</b>
            </p>
          </div>
        </div>
      </div>
      <figure class="foto-presentacion">
        <!-- <img class="foto-perfil" src="../assets/img/daniel.png" alt="" /> -->
      </figure>
    </section>
    <section class="content">
      <div>
        <div class="about">
          <!-- <img src="../assets/img/wallpaper32.jpg" alt=""> -->
            

          <p>
            <a>Hi, I'm Daniel. Nice to meet you</a>
            <br>
            <br>
            Since beginning my journey as a full stack developer nearly
            <b>2</b> years ago, I've done remote work for agencies, and
            collaborated with talented people to create digital products for
            both business and consumer use.<br /><br />I'm quietly confident,
            naturally curious, and perpetually working on improving my chops one
            design problem at a time.
          </p>
        </div>
      </div>
      <div class="technologies">
        <h1>SKILLS</h1>
        <figure>
          <img src="../assets/img/logo-python.png" alt="" />
          <img src="../assets/img/logo-js.png" alt="" />
          <img src="../assets/img/logo-django.png" alt="" />
          <img src="../assets/img/logo-vue.png" alt="" />
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
</style>
