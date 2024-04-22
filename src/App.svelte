<script>
	import router from 'page';
	import Home from './pages/Home.svelte';
	import Login from './pages/Login.svelte';
	import Register from './pages/Register.svelte';
	
	let page;

	router("/", () => (page = Home));
	router("/login", () => (page = Login));
	router("/register", () => (page = Register));

	router.start();
</script>

<svelte:component this={page} />