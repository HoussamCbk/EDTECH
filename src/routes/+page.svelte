<script>
    import Hero from "../components/hero.svelte"
    import Splash from "../components/splash.svelte";
    import Nav from "../components/nav.svelte";
    import About from "../components/about.svelte"
    import Further from "../components/further.svelte"
    import Link from "../components/Link.svelte";
</script>

<svelte:head>
  <!-- HTML Meta Tags -->
  <title>EDTECH AI - Hackathon ENSAMc</title>
  <meta name="description" content="EDTECH AI HACKATHON, un événement visant l’innovation des solutions en technologie éducative.">

  <!-- Google / Search Engine Tags -->
  <meta itemprop="name" content="EDTECH AI Hackathon">
  <meta itemprop="description" content="EDTECH AI HACKATHON, un événement visant l’innovation des solutions en technologie éducative.">
  <meta itemprop="image" content="/meta.png">

  
</svelte:head>

<Nav/>
<Hero/>
<Splash/>
<About />
<Further />



<footer>
    <div>
        <h2>EDTECH AI Hackathon!</h2>
        <p>Ecole Nationale Supérieure d'Arts et Métiers Casablanca</p>
        <p>Made by Choubik Houssam</p>
    </div>   

    <div class="logos">
        <a href="https://example.com/logo1" target="_blank">
            <img src="logo1.png" alt="Logo 1">
        </a>
        <a href="https://example.com/logo2" target="_blank">
            <img src="logo2.png" alt="Logo 2">
        </a>
        <a href="https://example.com/logo3" target="_blank">
            <img src="logo3.png" alt="Logo 3">
        </a>
    </div>
</footer>

<style>
    footer {
        display: flex;
        background-color: #8338ec;
        justify-content: space-between;
        align-items: center;
        color: black;
        flex-wrap: wrap;
        padding: 1.2rem 2rem;
    }
    
    footer > div > h2 {
        text-align: left;
        font-size: 3em;
        line-height: 1;
        margin-block-end: 0em;
    }

    footer > div > p {
        margin-block-start: 0.7em;
        line-height: 1.5;
        margin-block-end: 0em;
    }

    .logos {
        display: flex;
        gap: 1rem;
    }

    .logos a {
        display: inline-block;
        transition: transform 0.3s ease;
    }

    .logos a:hover {
        transform: scale(1.1);
    }

    .logos img {
        height: 50px; /* Adjust as needed */
        width: auto;
    }
</style>

