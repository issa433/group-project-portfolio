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

<style>

    .slideElias img {
     width: 100%;
     height: 100vh;
     object-fit: cover;
     display: block;
    }
 .page {
    position: absolute;
    top: 100px;
    right: 60px;
    z-index: 1;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
}

.fotogalleri {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 16px;
    max-width: 1100px;
    margin: 40px auto;
    padding: 0 20px;
}
.fotogalleri img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 8px;
    transition: transform 0.3s ease;
}
.fotogalleri img:hover {
    transform: scale(1.05);
}
</style>