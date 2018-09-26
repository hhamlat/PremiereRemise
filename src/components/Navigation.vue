<template>
  <nav>
    <div id="menu">
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/album">Album</router-link>
        </li>
        <li>
          <router-link to="/artist">Artist</router-link>
        </li>
        <li>
          <router-link to="/artist">Artist</router-link>
        </li>
        <li>
          <router-link to="/artist">Artist</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>


<style>
  #menu{
    width: 20%;
    background-color: red;
    float: left;
    height: 20%;
  }
  #menu li:hover {
    background-color: beige; /* Dark grey background on mouse-over */
  }
</style>
