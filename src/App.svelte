<script>
	import { Router, Route, navigate } from "svelte-routing";

	import Auth from "./Layout/Auth.svelte";
	import Common from "./Layout/Common.svelte";
  import Redirect from "./Views/Redirect.svelte";
  
	export let url = "";
</script>
  
<Router url="{url}">
<!-- Layout -->
<Route path="/login" component="{Common}" />
<Route path="/*auth" component="{Auth}" />
</Router>