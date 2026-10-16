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
    background-color: rgba(255, 255, 255, 0.621);
    padding: 24px 32px;
    border-radius: 12px;
    max-width: 400px;
    width: 100%;
}
</style>