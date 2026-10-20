<script>
    let sent = $state(false);
    let name = $state ('');
    function handleSubmit(event) {
        event.preventDefault();
        sent = true;
    }
</script>

<main>
<img src="/eliasContact.jpeg" alt="Portratt av fotografen Elias" />

<div class="page">
    {#if sent}
        <h1>Thank you, {name}!</h1>
        <p>I will get back to you as soon as possible.</p>
    {:else}
        <h1>Please contact me here</h1>
        <p>Fill out the form below to send me a message.</p>
        <form onsubmit={handleSubmit}>
            <label for="name">Your name:</label>
            <input type="text" id="name" bind:value={name} required />

            <label for="message">Your message:</label>
            <textarea id="message" name="message" rows="6"></textarea>

            <button type="submit">Send</button>
        </form>
    {/if}
    <a href="/">Back to home</a>
</div>
</main>


<style>
h1 {
    color: white;
    font-size: 50px;
    text-shadow: 0 2px 20px rgba(0,0,0,0.5);
}
p, label {
    color: white;
    font-size: 17px;
}
.page a {
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    font-size: 14px;
}
img {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter:brightness(0.55);
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
input, textarea {
    padding: 8px;
    font-size: 16px;
    border: 2px solid white;
    background: rgba(0, 0, 0, 0.45);
    color: white;
    border-radius: 6px;
    font-family: inherit;
    resize: none;
    }
button {
    padding: 8px 16px;
    font-size: 16px;
    background-color: white;
    color: black;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    }
main {
    position: relative;
    display: flex;
    justify-content: flex-start;
    padding-left: 90px;
    align-items: center;
    height: 100vh;
}
.page {
    max-width: 400px;
    width: 100%;
}
</style>