<template>
  <div class="container">
  <h2> Login User my aap</h2>
  <br>
  <h1> Baby Name Generator</h1>
  <p>Chose your option and click the "Find Name" butoon below</p>

    <div class="tom-container">
      <div class="tom-container">
        <h4> 1) Chose a gender</h4>
          <div class="tom-container">
            <button class="tombtn">boy</button>
            <button class="tombtn">Unisex</button>
            <button class="tombtn">Girl</button>
          </div>
      </div>

      <div class="tom-container">
        <h4> 2) Chose the name's poopularity</h4>
          <div class="tom-container">
            <button class="tombtn">trandy</button>
            <button class="tombtn">Uniqe</button>
          </div>
      </div>

      <div class="tom-container">
        <h4> 3) Chose name's length</h4>
          <div class="tom-container">
            <button class="tombtn">long</button>
            <button class="tombtn">all</button>
            <button class="tombtn">Short</button>
          </div>
      </div>

    </div>  
  </div>

</template>

<style scoped>
.container{
  font-family: Arial, Helvetica, sans-serif;
  color: rgb(27,60,138);
  max-width: 50rem;
  margin: 0 auto;
  text-align: center;
}
h1{
  font-size:3rem;
}
.tom-container{
background-color: rgb(226, 236, 76);
border-radius: 1rem;
padding: 0.5rem; 
width: 90%;
margin: 0 auto;
margin-top: 1rem;

position: relative;
}
.tom-container{
  margin-bottom: 0.5rem;
}
.tombtn{
  background-color: white;
  outline: 0.15rem solid rgb(249,87,89);
  border: none;
  padding: 0.75rem;
  width: 10rem;
  font-size: 1rem;
  color: rgb(27,60,138);
  cursor: pointer ;
  font-weight: 200;
}

</style>

