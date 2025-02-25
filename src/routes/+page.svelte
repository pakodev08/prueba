<script>
    let hola = $state(`Hola`)
</script>

<h1>Welcome to your library project</h1>
<p>Create your package using @sveltejs/package and preview/showcase your work with SvelteKit</p>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<h1>{hola}</h1>
<a href="./dos"> Ir a la segunda pagina</a>

<!-- <script>
    import { Router, Route, Link } from "svelte-routing";

	import Dos from "./+dos.svelte";
  </script>
  
  <Router>
    <main>
      <Route path="/"  />
      <Route path="/dos" component={Dos} />
    </main>
  </Router> -->