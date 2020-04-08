<template>
  <div class="home">


    <div class="jumbotron">
      <img src="../assets/desktop.jpeg" alt="dekstop">
    </div>
    <h1>BootCamp Program</h1>
      <div class="container">
        <div class="row">
          <div class="col-12">
            <table class="table">
  <thead>
    <tr>
      <th scope="col">No.</th>
      <th scope="col">Program</th>
    
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>{{frontend1}}</td>
    
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>{{frontend2}}</td>
     
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>{{frontend3}}</td>
     
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>{{db}}</td>
     
    </tr>
      <tr>
      <th scope="row">5</th>
      <td>{{backend}}</td>
     
    </tr>
  </tbody>
</table>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.min.css'

export default {
  name: 'Profile',
  data: function(){
    return  {
      frontend1:"HTML",
      frontend2:"CSS",
      frontend3:"JS",
      db:"MySQL",
      backend:"PHP "

    }
  },
  components: {}
}
</script>
