<template>

        <head>
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1">
          <title>Bootstrap demo</title>
          <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
        </head>
      <div class="container">
          <div class="alert bg-success my-3">
              <h4 class="text-center" style="color: white">create account(signup) </h4>
           </div>                    
      </div>                          
      <div class="container">
              <div class="row">
                  <div class="col"></div>
                  <div class="col">
                      <form action="/user/signup" method="post"> <!--either get or post-->
                          <div class="field my-3">
                              <label for="" class="form-label">FirstName:</label>
                              <input type="text" class="form-control" name="firstname" placeholder="Enter your firstname">
                          </div>
                          <div class="field my-3">
                              <label for="" class="form-label">Lastname:</label>
                              <input type="text" class="form-control" name="lastname" placeholder="enter lastname">
                              </div>
                          <div class="field my-3">
                              <label for="" class="form-label">mobno:</label>
                              <input type="text" class="form-control" name="mobno" placeholder="enter mob no">
                              <div class="field my-3">
                                  <label for="" class="form-label">email:</label>
                                  <input type="text" class="form-control" name="email" placeholder="enter email"></div>
                                  <div class="field my-3">
                                      <label for="" class="form-label">password:</label>
                                      <input type="text" class="form-control" name="password" placeholder="enter pass"></div>
                                      <div class="field my-3">
                                          <label for="" class="form-label">Usertype:</label>
                                          <input type="text" class="form-control" name="usertype" placeholder="enter usertype(1-admin,2-normal)"></div>
                                  </div>
                          <input type="submit" value="signup" class="btn btn-danger my-3 w-100">
                      </form>
                  </div>
                  <div class="col"></div>
              </div>
          </div>

</template>

<script>
export default {
  name: 'MyHome',

}

</script>