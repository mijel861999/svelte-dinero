<script>
  import { Router, Link, Route } from "svelte-routing";

  import Login from "./views/Login.svelte";
  import About from "./views/About.svelte";
  import Home from "./views/Home.svelte";

  export let url = "";
</script>

<main>
  <Router {url}>
    <nav>
      <Link to="/">Home</Link>
      <Link to="/login">Login</Link>
    </nav>
    <div>
      <Route path="login" component={Login} />
      <Route path="/"><Home /></Route>
    </div>
  </Router>
</main>

<style>
</style>
