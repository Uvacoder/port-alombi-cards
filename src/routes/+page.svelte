<script>
    import Header from '$lib/components/Header.svelte';
</script>

<svelte:head>
    <title>uvacoder</title>
</svelte:head>

<Header lang="en" />
<div class="title">
    <h1>Welcome!</h1>
    <h2>Pick your poison</h2>
</div>

<h2>Recently updated </h2>
<div class="box-container">
    <a target="_blank" rel="noreferrer" href="https://github.com/uvacoder/port-alombi-cards">
        <div class="box">
            <h4>Homepage</h4>
            <p>My personal website</p>
            <div class="pill-container"><p class="pill svelte">sveltekit</p></div>
        </div>
    </a>
    <a target="_blank" rel="noreferrer" href="https://github.com/uvacoder/abcportfolio15">
        <div class="box">
            <h4>abcportfolio15</h4>
            <p>Portfolio using notion API</p>
            <div class="pill-container"><p class="pill typescript">notion</p></div>
        </div>
    </a>
    <a target="_blank" rel="noreferrer" href="https://github.com/shareablehq/shareable">
        <div class="box">
            <h4>Shareable </h4>
            <p>A web platform to share and browse Scriptable's scripts</p>
            <div class="pill-container"><p class="pill svelte">sveltekit</p></div>
        </div>
    </a>
    <a target="_blank" rel="noreferrer" href="https://github.com/alombi/earthquakes">
        <div class="box">
            <h4>earthquakes</h4>
            <p>A web application for monitoring earthquakes in Italy</p>
            <div class="pill-container"><p class="pill javascript">javascript</p></div>
        </div>
    </a>
</div>
<br><br>
