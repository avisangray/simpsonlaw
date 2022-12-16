<script>
	import Header from './Header.svelte';
	import './styles.css';
</script>
<svelte:head>
	<link href="https://fonts.googleapis.com/css?family=Work+Sans:300,400,700" rel="stylesheet">
	
	<!-- Animate.css -->
	<link rel="stylesheet" href="/animate.css"> 
	<link rel="stylesheet" href="/icomoon.css"> 
	<link rel="stylesheet" href="/bootstrap.css"> 
	<link rel="stylesheet" href="/magnific-popup.css"> 
	<link rel="stylesheet" href="/owl.carousel.min.css">
	<link rel="stylesheet" href="/owl.theme.default.min.css"> 
	<link rel="stylesheet" href="/flexslider.css"> 
	<link rel="stylesheet" href="/flaticon.css">
 
	<link rel="stylesheet" href="/style.css">
 
	<script src="/modernizr-2.6.2.min.js"></script>

	<!-- jQuery -->
	<script src="/jquery.min.js"></script>
	<!-- jQuery Easing -->
	<script src="/jquery.easing.1.3.js"></script>
	<!-- Bootstrap -->
	<script src="/bootstrap.min.js"></script>
	<!-- Waypoints -->
	<script src="/jquery.waypoints.min.js"></script>
	<!-- Stellar Parallax -->
	<script src="/jquery.stellar.min.js"></script>
	<!-- Carousel -->
	<script src="/owl.carousel.min.js"></script>
	<!-- Flexslider -->
	<script src="/jquery.flexslider-min.js"></script>
	<!-- countTo -->
	<script src="/jquery.countTo.js"></script>
	<!-- Magnific Popup -->
	<script src="/jquery.magnific-popup.min.js"></script>
	<script src="/magnific-popup-options.js"></script>
	<!-- Main -->
	<script src="/main.js"></script>


</svelte:head>
<div class="app">
	<Header />

	<main>
		<slot />
	</main>
 
</div>

<style>
	
	
</style>
