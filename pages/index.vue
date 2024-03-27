<template>
  <div class="home-page">
    <NavBar />
    <div class="about-box">
      <p class="paragraph">Philip Queen is a software developer currently having a great time working on 
        <a href="https://github.com/freemocap/freemocap">Freemocap</a>, 
        a free open source markerless motion capture software. He works actively on feature development, including building
        new backend systems to add functionality and increase efficiency. He also provides user support on GitHub and 
        the <a href="https://discord.gg/SgdnzbHDTG">Freemocap Discord</a>.</p>
      
      <p class="paragraph">Philip is also a dedicated member of the slackline/highline community. He heads, and wrote the curriculum for, 
        the Paradise Highline Community Rigging School. He has been on the International Slackline Association (ISA) Safety 
        Commision since 2020, and is a Senior Instructor for the ISA Rigging Certs. He also writes a very nerdy
        <a href="https://philipqueen.github.io/SlackBlog/">slackline blog</a>.</p>
    </div>

    <div class="about-image-box">
      <figure>
        <img src="/images/cropped_headshot.jpg" alt="Outdoor Headshot" style="width: 514px; height: 640px;">
        <figcaption style="font-size: 80%;">Photo by <a href="https://conordonadio.com/">Conor Donadio</a></figcaption>
      </figure>
    </div>
  </div>
</template>

<script lang="ts">

</script>

<style>
  .paragraph {
    margin-bottom: 1em;
  }

  a {
    color: blue;
  }

  a:hover {
    text-decoration: underline;
  }

  .about-box {
    display: inline-block;
    vertical-align: top;
    width: 400px;
    height: 300px;
    margin: 20px;
    padding: 10px;
  }

  .about-image-box {
    display: inline-block;
    vertical-align: middle;
    width: 550px;
    height: 640px;
    margin: 10px;
  }

</style>
