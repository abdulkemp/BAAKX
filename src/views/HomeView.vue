<template>
  <div>
    <div class="card">
      <div class="card-header">
        Savings Account
      </div>
      <div class="card-body">
        <blockquote class="blockquote mb-0">
          <p>Current Balance : R30 078</p>
        </blockquote>
      </div>
    </div>
  </div>
  <div>
    <div class="card">
      <div class="card-header">
        Fixed Account
      </div>
      <div class="card-body">
        <blockquote class="blockquote mb-0">
          <p>Current Balance : R13 100</p>
        </blockquote>
      </div>
    </div>
  </div>
  <div>
    <div class="card">
      <div class="card-header">
        Emergency Account
      </div>
      <div class="card-body">
        <blockquote class="blockquote mb-0">
          <p>Current Balance : R4 870</p>
        </blockquote>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>
.card{
  display: flex;
  justify-content: center;
  margin: 50px;
  border: 1px solid black;
}

.card-header{
  background-color: rgb(109, 30, 30);
  color: white;
}

.card-body{
  background-color: rgb(34, 33, 33);
  color: white;
}
</style>
