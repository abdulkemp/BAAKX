<template>
    <div class="space">
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
    </div>
   
    <div>
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
              Launch demo modal
          </button>
  
          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
              <div class="modal-dialog">
                  <div class="modal-content">
                      <div class="modal-header">
                          <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                          ...
                      </div>
                      <div class="modal-footer">
                          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                          <button type="button" class="btn btn-primary">Save changes</button>
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </template>
  
  <script>
  // @ is an alias to /src
  // import HelloWorld from '@/components/HelloWorld.vue'
  
  export default {
    // name: 'HomeView',
    // components: {
    //   HelloWorld
    // }
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
  .space{
    margin-top: 150px;
  }
  </style>
  