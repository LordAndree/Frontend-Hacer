<script>
	import router from 'page';
	import Home from './pages/Home.svelte';
	import Login from './pages/Login.svelte';
	import Register from './pages/Register.svelte';
    import Dashboard from './pages/Dashboard.svelte';
	
	let page;

	router("/", () => (page = Home));
	router("/login", () => (page = Login));
	router("/register", () => (page = Register));
	router("/dashboard", () => (page = Dashboard));

	router.start();
</script>

<svelte:component this={page} />