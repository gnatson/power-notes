<script>
  let content = 'This is sample content'
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Fira+Code&display=swap');

  main {
    font-family: 'Press Start 2P', cursive;
    background-color: #282c34;
    color: #abb2bf;

    user-select: none;
  }

  #not-ready-yet {
    width: 100vw;
    height: 100vh;

    display: flex;
    justify-content: center;
    align-items: center;
    flex-flow: column;

    filter: drop-shadow(3px 5px 2px rgb(0 0 0 / 0.4));
    /* box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px; */
  }

  a {
    color: aqua;
    text-decoration: none;
    animation: 0.5s rotateCorner infinite alternate;
  }

  @keyframes rotateCorner {
    0% {
      transform-origin: top left;
      transform: rotate(2deg);
    }

    50% {
      transform: scale(1.05);
    }

    100% {
      transform-origin: bottom right;
      transform: rotate(-2deg);
    }
  }
</style>

<!-- <textarea name="" id="" cols="30" rows="10" bind:value={content} /> -->
<main>
  <div id="not-ready-yet">
    <h1>📘 PowerNotes</h1>
    <h2>app coming soon...</h2>
    <a href="https://github.com/gnatson/power-notes" target="_blank">
      ⚡ GitHub Repo
    </a>
  </div>

</main>
