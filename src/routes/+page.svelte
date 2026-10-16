

<main>
    <div class="page">
        <h1>Welcome to our project</h1>
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

<footer>
    <a href="#top">Back to top</a>
    <a href="/contact">Contact me</a>
</footer>

</main>

<style>
img {
    width: 100%;
    height: 100vh;
    object-fit: cover;
    display: block;
}
main {
    position: relative;
    height: 100vh;
    overflow-y: scroll;
    scroll-snap-type: y mandatory;
    scroll-behavior: smooth;
}
.slide {
    scroll-snap-align: start;
    scroll-snap-stop: always;
}
footer {
    scroll-snap-align: end;
    padding: 24px 40px;  
} 

.page {
    position: absolute;
    top: 100px;
    left: 60px;
    z-index: 1;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
}
:global(body) {
    margin: 0;
}
</style>
