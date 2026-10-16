<main>
    <div class="page">
     <h1>About me</h1>
       <p>Hello! my name is Elias.</p>
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
    margin: 40px 0;
    padding: 0 16px;
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
    transform: scale(1.15);
    z-index: 2;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0,4);
}
</style>