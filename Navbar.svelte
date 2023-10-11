<script>
    import {goto} from '$app/navigation';

    
</script>

<main>
    <p>
        Hello, my name is John. <span>John is cool.</span> Be like John.
      </p>
      <form>
        <label>Username</label>
        <input type="text" />
        <label>Password</label>
        <input type="password" />
        <input type="checkbox" />
        <small>Stay logged in?</small>
        <button on:click>Login</button>
      </form>
</main>