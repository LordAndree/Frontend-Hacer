<!-- Login Page -->
<script>
    let username = '';
    let password = '';
	let imageURL = "image/logo.png"

    function handleLogin() {
        // Lakukan sesuatu ketika tombol login ditekan, misalnya validasi atau permintaan HTTP ke server
        console.log("Username:", username);
        console.log("Password:", password);
    }
</script>

<style>
	.body {
		margin: 0;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
	}	

	.container {
		max-width: 400px;
		padding: 20px;
		border: 1px solid #ccc;
		border-radius: 5px;
		box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
		text-align: center;
		margin-top: 13%;
		margin-bottom: 100%;
		margin-left: 40%;
		margin-right: 40%;
		/* margin: auto;  */
	}


    .logo {
        width: 100px;
        margin-right: 20px;
        vertical-align: middle;
    }

    .input-group {
        margin-bottom: 20px;
        text-align: left;
    }

    .input-group input {
        width: calc(100% - 10px);
        padding: 10px;
        margin-top: 5px;
        border: 1px solid #ccc;
        border-radius: 5px;
        box-sizing: border-box;
    }

    .input-group label {
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
    }

    .login-button {
        background-color: #007bff;
        color: #fff;
        border: none;
        border-radius: 5px;
        padding: 10px 20px;
        cursor: pointer;
        transition: background-color 0.3s;
    }

    .login-button:hover {
        background-color: #0056b3;
    }
</style>

<div class="container">
    <img src="{imageURL}" alt="Logo" class="logo">
    <div class="input-group">
        <label for="username">Username</label>
        <input type="text" id="username" bind:value={username} />
    </div>
    <div class="input-group">
        <label for="password">Password</label>
        <input type="password" id="password" bind:value={password} />
    </div>
    <button on:click={handleLogin} class="login-button">Login</button>
</div>
