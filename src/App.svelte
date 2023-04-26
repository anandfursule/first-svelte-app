<script>
  function handleClick() {
    alert('You clicked the button!');
  }
</script>

<style>
  :global(body) {
    margin: 0;
    font-family: Arial, sans-serif;
  }

  header {
    background-color: #4caf50;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 2rem;
  }

  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: calc(100vh - 6rem);
  }

  button {
    background-color: #4caf50;
    color: white;
    border: none;
    padding: 1rem 2rem;
    font-size: 1.5rem;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  button:hover {
    background-color: #3f8c40;
  }

  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 1rem;
  }
</style>

<header>
  My Landing Page
</header>

<main>
  <button on:click={handleClick}>
    Click me!
  </button>
</main>

<footer>
  &copy; 2023 My Company
</footer>