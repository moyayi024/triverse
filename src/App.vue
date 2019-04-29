<template>
  <div id="app">
    <div class="container-fluid">
      <!-- Triverse -->
      <div class="row">
        <div class="col-sm-8">
             <div style="padding:80px;">
                <div class="row" >
                <h1>Welcome to Triverse</h1>
                <div style="color:white; padding-top:10px; font-size:20px;"> 
                  <p><b>Triverse is an app that can help you and your community to have easy access for information, news and update in your area.</b></p>
                </div>
                <div class="col-xs-4">
                  <div>
                    <img class="responsive" alt="Vue logo" style="text-align:center; margin-bottom:10px;" src="./assets/web.png" width="260" height="218">
                  </div>
                </div>
                <div class="col-xs-4">
                  <div style="padding-top:80px;padding-left:10px;">
                    <img class="responsive" alt="Vue logo" style="text-align:center; margin-bottom:10px;" src="./assets/mobile.png" width="86" height="132">      
                  </div>
                </div>  
             </div>
           </div>
        </div>
        <!-- Login -->
        <div class="col-sm-4"  style="background-color:#F5F5F5; padding:0px; height:100vh;">
          <div class="text-center" style="padding:50px">
           <div class="text-center">
             <img class="responsive" alt="Vue logo" style="text-align:center; margin-bottom:10px;" src="./assets/logotriverse.png" width="250" height="250">
          </div>
          <div class="login-dark">
            <form method="post">
              <h2 class="sr-only">Login Form</h2>
              <div class="illustration"><i class="icon ion-ios-locked-outline"></i></div>
              <div class="form-group"><input class="form-control" type="email" name="email" placeholder="Email"></div>
              <div class="form-group"><input class="form-control" type="password" name="password" placeholder="Password"></div>
              <div class="form-group"><button class="btn btn-primary btn-block" type="submit">Log In</button></div><a href="#" class="forgot">Forgot your email or password?</a>
            </form>
          </div>
          </div>  
         
          <div style="background-color:#42f4a1;width:100%; position:absolute; bottom: 0;">
              <div class="text-center" style="color:white; padding-top:10px;"> <p>By continuing you accept our <b>Terms of Use</b></p></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'app',
//   components: {
//     HelloWorld
//   }
// }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  
}
</style>