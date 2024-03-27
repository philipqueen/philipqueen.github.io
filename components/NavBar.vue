<template>
  <nav>
    <ul id="nav">
      <li><nuxt-link to="/"><b>Philip Queen</b></nuxt-link></li>
      <li><nuxt-link to="/contact">Contact</nuxt-link></li>
      <li><a href="https://github.com/philipqueen" target="_blank">Github</a></li>
    </ul>
    <hr>
  </nav>
</template>

<script lang="ts">

</script>

<!-- Add your styles here -->
<style>
  #nav {
	list-style: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
    }

    #nav li {
        float: left;
        vertical-align: bottom;
    }

    #nav li a {
        display: block;
        color: black;
        text-align: center;
        padding-left: 16px;
        padding-right: 16px;
        padding-top: 5px;
        text-decoration: none;
    }

    #nav li a:hover {
        text-decoration: underline;
    }
</style>