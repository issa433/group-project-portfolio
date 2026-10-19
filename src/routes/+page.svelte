

<main>
    <div class="page">
        <h1>Elias Berg</h1>
        <p>Welcome to my portfolio!</p>
        <a href="/about">About me</a>
        <a href="/contact">Contact me</a>
    </div>

    <div class="slide Elias" id="top">
        <img src="/elias-profilbild.jpeg" alt="Portratt av fotografen Elias" />
    </div>

    <div class="slide restaurang" id="top">
        <img src="/restaurang.jpeg" alt="Restaurang" />
    </div>
    <div class="slide restutant" id="top">
        <img src="/resturant.jpeg" alt="Restaurant" />
    </div>

    <div class="slide mat" id="top">
        <img src="/Mat.jpeg" alt="Mat" />
    </div>
</main>

<footer>
    <a href="#top">Back to top</a>
    <a href="/about">About me</a>
    <a href="/contact">Contact me</a>
</footer>

<style>
h1 {
    color: #032344;
    font-size: 70px;
}
p {
    color: #032344;
    font-size: 30px;
}
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
    top: 100px;
    left: 90px;
    z-index: 0;
    background-color: rgba(255, 255, 255, 0.619);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
}
:global(body) {
    margin: 0;
}
footer {
    position: bottom;
    width: 100%;
    background-color: rgba(247, 236, 200, 0.8);
    padding: 8px 16px;
    text-align: center;
}
</style>
