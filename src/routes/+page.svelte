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

    <div class="slide restaurang">
        <img src="/restaurang.jpeg" alt="Restaurang" />
    </div>

    <div class="slide restaurant">
        <img src="/resturant.jpeg" alt="Restaurant" />
    </div>

    <div class="slide mat">
        <img src="/Mat.jpeg" alt="Mat" />
    </div>
</main>

<footer>
    <a href="#top">Back to top</a>
    <a href="/about">About me</a>
    <a href="/contact">Contact me</a>
</footer>

<style>
:global(html) {
    scroll-snap-type: y mandatory;
    scroll-behavior: smooth;
}
.slide {
    scroll-snap-align: start;
}
h1 {
    color: #f6f8f9;
    font-size: 70px;
    text-shadow: 0 2px 20px rgba(0,0,0,0.5);
}
p {
    color: #fbfdff;
    font-size: 30px;
    text-shadow: 0 2px 20px rgba(0,0,0,0.5);
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
    z-index: 1;
    max-width: 400px;
}
.page a {
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    font-size: 14px;
    margin-right: 24px;
    text-shadow: 0 2px 20px rgba(0,0,0,0.5);
}
:global(body) {
    margin: 0;
}
footer {
    scroll-snap-align: end;
    background-color: black;
    padding: 24px 16px;
    text-align: center;
}
footer a {
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    font-size: 12px;
    margin: 0 16px;
}
</style>