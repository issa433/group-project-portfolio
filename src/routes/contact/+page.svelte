<a href="/">Back to home</a>
<main>
<img src="/eliasContact.jpeg" alt="Portratt av fotografen Elias" />

<div class="page">
    <h1> Please contact me here</h1>

    <form>
     <label for="name">Your name:</label>
     <input type="text" id="name" name="name" />
    
     <lable for="message">Your message:</lable> 
     <textarea id="message" name="message" rows="6"></textarea>

     <button type="submit">Send</button>
    </form>
 </div>
</main>


<style>
h1 {
    color: #19232d;
}
p {
    color: #19232d;
}
img {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
}
 form {
    display: flex;
    flex-direction: column;
    text-align: left;
    gap: 8px;
    max-width: 400px;
    margin-bottom: 24px;
    }
textarea {
    padding: 8px;
    font-size: 16px;
    border: 1px solid #9c9ea2;
    border-radius: 6px;
    font-family: inherit;
    }
button {
    padding: 8px 16px;
    font-size: 16px;
    background-color: #19232d;
    color: rgb(224, 224, 224);
    border: none;
    border-radius: 6px;
    cursor: pointer;
    }
main {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.page {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
    width: 100%;
}
</style>