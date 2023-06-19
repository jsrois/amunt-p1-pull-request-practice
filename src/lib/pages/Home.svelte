<script>
    export let ctaText = 'Get Started';
    import backgroundImage from '../../assets/background.png'
</script>

<main>
    <div class="background-image" style="background-image: url({backgroundImage})"></div>
    <div class="content">
        <h1>Welcome to Our Shop!</h1>
        <p>Find the best for your best friend</p>
        <button>{ctaText}</button>
    </div>
</main>

<style>
    main {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .background-image {
        position: absolute;
        width: 100%;
        height: 100vh;
        background-size: cover;
        background-position: center;
        opacity: 0.5;
    }

    .content {
        text-align: center;
        z-index: 1;
    }

    h1 {
        font-size: 2.5rem;
        margin-bottom: 1rem;
    }

    p {
        font-size: 1.2rem;
        margin-bottom: 2rem;
    }

    button {
        padding: 10px 20px;
        font-size: 1rem;
        background-color: #2fffff;
        color: #fff;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
</style>
