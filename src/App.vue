<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  
  export default {
    components: {
      
    }
};
</script>

<style>
:root {
  --primary: #f18805;
  --secondary: #24262b;
  --white: #fff;
  --lightgray: #edeff2;
  --darkgray: #292621;
}

body {
  font-family: "Jost", sans-serif;
  font-weight: normal;
  font-style: normal;
  font-size: 16px;
}
.btn_1 {
  background: #292621;
  font-weight: 500;
  border: 1px solid #292621;
  text-transform: uppercase;
  color: #fff !important;
  display: inline-block;
  padding: 15px 47px;
  line-height: 16px;
  font-size: 14px;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Jost", sans-serif;
  color: #292621;
  margin-top: 0px;
  font-style: normal;
  font-weight: 500;
  text-transform: normal;
}

p {
  font-family: "Jost", sans-serif;
  color: #301a22;
  font-size: 16px;
  line-height: 30px;
  margin-bottom: 15px;
  font-weight: 400;
  line-height: 1.6;
}

ul {
  margin: 0;
  padding: 0;
}

li {
  list-style: none;
}

a,
button {
  color: var(--white);
  outline: medium none;
}

a,
.button {
  -webkit-transition: all 0.3s ease-out 0s;
  -moz-transition: all 0.3s ease-out 0s;
  -ms-transition: all 0.3s ease-out 0s;
  -o-transition: all 0.3s ease-out 0s;
  transition: all 0.3s ease-out 0s;
}

a {
  color: #635c5c;
  text-decoration: none;
}

p {
  font-family: "Jost", sans-serif;
  color: #301a22;
  font-size: 16px;
  line-height: 30px;
  margin-bottom: 15px;
  font-weight: 400;
  line-height: 1.6;
}
</style>