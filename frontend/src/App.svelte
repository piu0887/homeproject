<script>
  import Router from 'svelte-spa-router'
  import Home from "./routes/Home.svelte"
  import Navigation from "./components/Navigation.svelte"
  import UserCreate from "./routes/UserCreate.svelte"
  import UserLogin from "./routes/UserLogin.svelte"



  const routes = {
    '/': Home,
    '/user-create': UserCreate,
    '/user-login': UserLogin,

  }
</script>

<Navigation />
<Router {routes}/>

