<script>
	import {Router, Route, Link} from "svelte-routing";
	import LoginPage from "./routes/LoginPage.svelte";
	import SignPage from "./routes/SignPage.svelte";
	import DashboardPage from "./routes/DashboardPage.svelte";

	let defaultRoute = "/login";
	if (window.location.pathname === "/") {
		window.location.pathname = defaultRoute;
	}

	// export let url="";
</script>

<Router >
	<!-- <nav>
		<Link to="/login">Login</Link>
		<Link to="/signup">Sign In</Link>
		<Link to="/dashboard">Home</Link>
	</nav> -->
	<!-- <Redirect from="/" to="/login"/> -->
	<!-- <div> -->
		<Route path="/login" component={LoginPage}/> <!-- -->
		<Route path="/signup" component={SignPage}/>
		<Route path="/dashboard" component={DashboardPage}/>
	<!-- </div> -->
</Router>