<script>
</script>

<nav class="navbar">
	<a href="/" class="nav-branding">Full Moon Escape</a>
	<ul id="nav-menu">
		<li class="nav-item">
			<a href="/rooms" class="nav-link">Rooms</a>
		</li>
		<li class="nav-item">
			<a href="/amenities" class="nav-link">Amenities</a>
		</li>
		<li class="nav-item">
			<a href="/gallary" class="nav-link">Gallary</a>
		</li>
        <li class="nav-item">
			<a href="/party" class="nav-link">Parties</a>
		</li>
		<li class="nav-item">
			<a href="/faq" class="nav-link">F.A.Q</a>
		</li>
	</ul>
    <div class="hamburger">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
    </div>
</nav>

<style>
    nav {
        background-color: rgba(0, 0, 0, 0.7);
    }
    li {
        list-style: none;
    }
    a{
        color: whitesmoke;
        text-decoration: none;
    }
    .navbar {
       min-height: 70px;
       display: flex; 
       justify-content: space-between;
       align-items: center;
       padding: 0 24px;
    }
    #nav-menu {
        display: flex;
        justify-content: space-around;
        align-items:flex-end;
        gap: 60px; 
    }
    .nav-branding {
        font-size: 2 rem;
    }
</style>
