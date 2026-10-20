<main>
    <div class="page">
     <h1>About me</h1>
       <p>I’m Elias Berg, a photographer specialising in food and interior photography for restaurants, cafés and bakeries. My approach is calm and natural, capturing the details, textures and atmosphere that make each place unique. From a bakery’s opening to a seasonal menu or a neighbourhood café, I create honest, inviting images that tell the story behind the space and the food.</p>
      <a href="/">Back to home</a>
    </div>

    <div class="slideElias" id="top">
        <img src="/elias+mat.jpeg" alt="Portratt av fotografen Elias" />
    </div>
    <div class="fotogalleri">
        <img src="/galleri1.jpeg" alt="Fisk" />
        <img src="/galleri2.jpeg" alt="Fisk" />
        <img src="/galleri3.jpeg" alt="Fisk" />
        <img src="/galleri4.jpeg" alt="Fisk" />
        <img src="/galleri5.jpeg" alt="Fisk" />
        <img src="/galleri6.jpeg" alt="Fisk" />
        <img src="/galleri7.jpeg" alt="Fisk" />
        <img src="/galleri8.jpeg" alt="Fisk" />
        <img src="/galleri9.jpeg" alt="Fisk" />
        <img src="/galleri10.jpeg" alt="Fisk" />
        <img src="/galleri11.jpeg" alt="Fisk" />
        <img src="/galleri12.jpeg" alt="Fisk" />
        <img src="/galleri13.jpeg" alt="Fisk" />
        <img src="/galleri14.jpeg" alt="Fisk" />
        <img src="/galleri15.jpeg" alt="Fisk" />
        <img src="/galleri16.jpeg" alt="Fisk" />
    </div>
</main>

<footer>
    <a href="#top">Back to top</a>
    <a href="/contact">Contact me</a>
</footer>

<style>
footer {
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
.slideElias img {
    width: 100%;
    height: 100vh;
    object-fit: cover;
    display: block;
    }
    .slideElias {
    position: relative;
}
.slideElias::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(to right, transparent 35%, rgba(0, 0, 0, 0.75));
}
 .page {
    position: absolute;
    top: 100px;
    right: 60px;
    z-index: 1;
    max-width: 400px;
}
.page h1 {
    color: white;
    font-size: 70px;
    text-shadow: 0 2px 20px rgba(0,0,0,0.5);
}
.page p {
    color: white;
    font-size: 18px;
    line-height: 1.6;
    text-shadow: 0 1px 8px rgba(0,0,0,0.6);
}
.page a {
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    font-size: 14px;
}
.fotogalleri {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 2px;
    margin: 40px 0;
    padding: 0 2px;
    overflow-x: clip;
}
.fotogalleri img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 8px;
    transition: transform 0.3s ease; box-shadow 0.3s ease;
    position: relative;
}
.fotogalleri img:hover {
    transform: scale(2);
    z-index: 2;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
}
.fotogalleri img:nth-child(4n + 1) {
    transform-origin: left center;
}
.fotogalleri img:nth-child(4n) {
    transform-origin: right center;
}

main {
    background-color: black;
    min-height: 100vh;
}

:global(body) {
    margin: 0;
    background-color: black;
    }
</style>