<script>
    export let lang;
    let url = '/'
    if(lang == 'it'){
        url = '/it'
    }
</script>

<div class="fake-nav"></div>
<nav>
    <div>
        <a href={url} class="name">uvacoder</a>
        {#if lang == 'it'}
            <a href="/it/blog">Blog</a>
            <a href="/it/blog">Foto</a>
        {/if}
        {#if lang == 'en'}
            <a target="_blank" rel="noreferrer" href="https://github.com/uvacoder">github</a>
        {/if}
    </div>
    <div>
        {#if lang == 'en'}
            <a href="/contacts">Contacts</a>
        {:else}
            <a target="_blank" href="https://github.com/uvacoder/port-alombi-cards">Source</a>
        {/if}
    </div>
</nav>


<style>
.fake-nav{
   position: fixed;
   top:0;
   left:0;
   width: 100%;
   height:50px;
   background-color: #1c1c1c;
   opacity: .6;
   z-index:3;
}
nav {
   position: fixed;
   top:0;
   left:0;
   width: 100%;
   height:50px;
   -webkit-backdrop-filter: blur(20px);
   backdrop-filter: blur(20px);
   z-index: 3;
}
</style>
