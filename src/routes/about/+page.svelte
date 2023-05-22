<script>

    let title = "All about the site!";
    const BASE_URL = "https://cataas.com/";

    let f = fetch(`${BASE_URL}/cat?json=true`);
    
    /* A note from the developer...

        I need a little help completing this part... I want to put a random cat from the above URL into the image tag below... 
        But I don't know how!

    */

</script>

<style>

    h1{
        color:#124632;
        font-size:32px;
        padding-top:20px;
        padding-left:30px;
        padding-right:30px;
        padding-bottom:20px;
    }

    h3{
        color:#124632;
        border-bottom:1px solid #124632;
    }

</style>

<nav>
    <ul>
        <a href="/">Home</a>
        <a href="/about">About</a>
    </ul>
</nav>

<h1>{title}</h1>

<p>
    Welcome to the about page! Look, a cat:
    <img src="" />
</p>

<footer>
    <h3>Site navigation</h3>
    <ul>
        <a href="/">Home</a>
        <a href="/about">About</a>
    </ul>
</footer>