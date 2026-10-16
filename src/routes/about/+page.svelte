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
    left: 60px;
    z-index: 1;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
}
</style>