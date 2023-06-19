<script>
    import logo from './assets/logo.png'
    import {Router} from 'svelte-routing'
    import Header from "./lib/components/Header.svelte";
    import Routes from "./lib/components/Routes.svelte";
</script>

<Router>
    <Header />
    <Routes />
</Router>

<style>
</style>