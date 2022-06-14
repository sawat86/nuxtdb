<template>
<div> 
  <DIV >
      <!-- navbar -->
      <b-navbar type="dark" variant="dark" >
        <div class="container ">
            <!-- Image and text -->  
            <b-navbar-brand href="#">
                <img src="https://cdn-icons-png.flaticon.com/128/5968/5968898.png" width="35" class="d-inline-block align-top" alt="Kitten">
                BootstrapVue
            </b-navbar-brand>
            <!-- manu bar -->
            <b-navbar-nav class="ml-auto">
              <b-nav-item active  href="#">Contact</b-nav-item>
              <b-nav-item href="#">About</b-nav-item>
            </b-navbar-nav>
        </div>    
      </b-navbar>
    </DIV> 
 <!-- from login -->
    <div class="container-from1">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="User"></b-form-input>
        </b-nav-form>
          <br>
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Password"></b-form-input>
        </b-nav-form>
          <br>
        <b-nav-form >
          <b-button size="sm" class="my-2 my-sm-0" type="submit">login</b-button>
      </b-nav-form>
    </div>
 

 <!-- civ ปิด -->
</div>
</template>



<!-- Css stlye -->
<style scoped>
.container-from1{


  background-color: rgb(184, 182, 182);
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 110px;
}

</style>

