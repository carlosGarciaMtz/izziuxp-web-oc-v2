<script>
	import { Router, Route } from "svelte-routing";

	// components for this layout
	// import Footer from "../components/Footer.svelte";
	import Login from "../Views/Login.svelte";
	
</script>

<div>
	<main class="login-page">
		<Router url="auth">
			<Route path="" component="{Login}" />
		</Router>		
	</main>
	<!-- <Footer/> -->
</div>