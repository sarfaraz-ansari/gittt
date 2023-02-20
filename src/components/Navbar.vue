<template>
  <div class="navbar">
    <div>
      <h1>SA</h1>
    </div>
    <ul>
      <li>
        <a href="#"><span>Home</span></a>
      </li>
      <li>
        <a href="#skills"><span>Skills</span></a>
      </li>
      <li>
        <a href="#main"><span>About</span></a>
      </li>
      <li>
        <a href="#footer"><span>Contact</span></a>
      </li>
    </ul>
  </div>
</template>
<script>
</script>
<style>
.navbar {
  height: 60px;
  width: 100%;
  background-color: #fff;
  line-height: 60px;
  box-sizing: border-box;
  /* position: fixed; */
}
.navbar div {
  float: left;
}
.navbar div h1 {
  float: left;
  width: 59px;
  height: 59px;
  margin-left: 10px;
  text-align: center;
  border-radius: 50%;
  color: #fff;
  background-color: black;
}
.navbar ul {
  float: right;
}
.navbar ul li {
  display: inline;
  padding: 5px;
  margin-right: 10px;
}
.navbar ul li a {
  text-decoration: none;
  color: black;
  font-size: 20px;
  padding: 5px;
  font-family: serif;
  font-weight: 700;
}

@media screen and (max-width: 830px) {
  .navbar div h1 {
    display: none;
  }
  .navbar ul li a {
    font-size: 18px;
  }

 
}
</style>
