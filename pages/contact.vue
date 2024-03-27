<template>
    <div class="home-page">
        <NavBar />
        <div class="contact-box">
            <p>Philip Queen can be reached by email at <a href="mailto:queen.philip@gmail.com?Subject=Website%20contact" target="_top">queen.philip@gmail.com</a>.</p>
        </div>

        <div class="contact-image-box">
            <a href="mailto:queen.philip@gmail.com?Subject=Website%20contact" target="_top" id="contact-image"></a>
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

    .contact-box {
        display: inline-block;
        vertical-align: top;
        width: 400px;
        height: 300px;
        margin: 10px;
        padding: 10px;
    }

    .contact-image-box {
        display: inline-block;
        vertical-align: middle;
        background-image: url("https://c2.staticflickr.com/4/3937/33315861544_370ca3bfaf_z.jpg");
        width: 512px;
        height: 640px;
        margin: 10px;
    }

    .contact-image-box:hover {
        background-image: url(https://c1.staticflickr.com/3/2884/33773750970_a353490398_z.jpg);
    }

    #contact-image a {
        background-image: url("https://c2.staticflickr.com/4/3937/33315861544_370ca3bfaf_z.jpg");
        width: 512px;
        height: 640px;
    }

    #contact-image a:hover {
        background-image: url(https://c1.staticflickr.com/3/2884/33773750970_a353490398_z.jpg);
    }
  
  </style>