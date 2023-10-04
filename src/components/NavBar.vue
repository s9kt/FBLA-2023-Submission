<template>
    <nav>
        <li class="nav-item-left"><a href="/">Home</a></li>
        <li class="nav-item-right"><a href="/login">Log In</a></li>
    </nav>
</template>

<style scoped>
nav {
  display: flex;
  list-style-type: none;
  flex-wrap: wrap;
  background-color: #10002B;
}

nav a {
  color: #ffffff;
}

nav a:hover {
  color:#E0AAFF;
}

nav li.nav-item-left {
  float: left;
  padding: 1em;
}

nav li.nav-item-right {
  margin-left: auto;
}
</style>