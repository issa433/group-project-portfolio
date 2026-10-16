

<main>
    <div class="page">
        <h1>Welcome to our project</h1>
        <p>Welcome to my portfolio!</p>
        <a href="/about">About me</a>
        <a href="/contact">Contact me</a>
    </div>

    <div class="Elias">
        <img src="/elias-profilbild.jpeg" alt="Portratt av fotografen Elias" />
    </div>

    <div class="restutant">
        <img src="/resturant.jpeg" alt="Restaurant" />
    </div>

    <div class="mat"
>
        <img src="/mat.jpeg" alt="Mat" />
    </div>
    <div class="sushi">
        <img src="/sushi.jpeg" alt="Sushi" />
    </div>

</main>
<footer>
    <a href="/">Back to top</a>
    <a href="/contact">Contact me</a>
</footer>

<style>
img {
    width: 100%;
    height: 100vh;
    object-fit: cover;
    display: block;
}
main {
    position: relative;
}
.page {
    position: absolute;
    top: 40px;
    left 40px;
    z-index: 0;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
}
:global(body) {
    margin: 0;
}
</style>
