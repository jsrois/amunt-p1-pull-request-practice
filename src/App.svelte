<script>
    import logo from './assets/logo.png'
    import {Router} from 'svelte-routing'
    import Header from "./lib/components/Header.svelte";
    import Routes from "./lib/components/Routes.svelte";
    import Información from "./lib/pages/Información.svelte";
</script>

<Router>
    <Header />
    <Routes />
    <Información />
</Router>

<style>
</style>