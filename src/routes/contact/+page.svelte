<h1> Please contact me here</h1>

<form>
    <label for="name">Your name:</label>
    <input type="text" id="name" name="name" />
    
    <lable for="message">Your message:</lable> 
    <textarea id="message" name="message" rows="6"></textarea>

    <button type="submit">Send</button>
</form>

<a href="/">Back to home</a>


<style>
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
        border: 1px solid #ccc;
        border-radius: 6px;
        font-family: inherit;
    }
button {
        padding: 8px 16px;
        font-size: 16px;
        background-color: #007BFF;
        color: white;
        border: none;
        border-radius: 6px;
        cursor: pointer;
    }
</style>