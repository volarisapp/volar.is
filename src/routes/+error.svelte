<script>
	import '$lib/style404.css';
</script>

<svelte:head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Are you lost? - 404</title>
	<link href="https://fonts.googleapis.com/css?family=Cabin:400,700" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Montserrat:900" rel="stylesheet">
</svelte:head>

<div id="notfound">
	<div class="notfound">
		<div class="notfound-404">
			<h3>Oops! Page not found</h3>
			<h1><span>4</span><span>0</span><span>4</span></h1>
		</div>
	    <h2>we are sorry, but the page you requested was not found</h2>
        <br>
        <a href="/">Return Home?</a>
        <br>
        <a onclick="history.back();return false;" href="#">Go back?</a>
	</div>
</div>