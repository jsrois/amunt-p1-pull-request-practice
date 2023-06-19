<script>
    import logo from "../../assets/logo.png";
    import {Link} from "svelte-routing";
</script>

<header>
    <img src={logo} alt="pet store icon">
    <nav>
        <Link to="/">Home</Link>
    </nav>
</header>

<style>
    header {
        height: 60px;
        background-color: #2fffff;
        display: flex;
        justify-content: space-between;
    }

    img {
        height: 100%;
    }
    nav {
        display: flex;
        align-items: center;
        padding: 20px;
    }
</style>