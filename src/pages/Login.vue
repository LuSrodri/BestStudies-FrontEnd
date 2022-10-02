<template>
    <div class="fullscreen bg-blue text-center q-pa-md flex flex-center">
      <div>
        <q-card class="my-card" style="width: 300px">
            <q-card-section>
                <h4 style="margin-bottom: 5px">Login</h4>
                <p>Faça seu login!</p>
                <hr>
            </q-card-section>
            <q-card-section>
                <q-form>
                <div class="row q-col-gutter-md">
                    <div class="col-12 col-md-6 col-sm-12">
                        <q-input outlined stack-label type="email" label="E-mail" />
                    </div>
                    <div class="col-12 col-md-6 col-sm-12">
                        <q-input outlined stack-label type="password" label="Senha"/>
                    </div>
                </div>
        
                <div class="q-mt-md">
                    <q-btn
                    label="Login"
                    type="submit"
                    color="primary"
                    />
                </div>
                <hr style="width: 200px; margin: 20px auto">
                <a href="/">Ou faça seu cadastro!</a>
                </q-form>
            </q-card-section>
        </q-card>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Login'
  }
  </script>
  