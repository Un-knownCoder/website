<section>
  <div class="hint">
    404 - Not found
  </div>

  <a href="/"><div class="back">Torna alla HOME</div></a>
</section>


<style>
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');
  * {font-family: "Open Sans", sans-serif;}
  a {
    text-decoration: none;
  }
  section {
    width: calc(100vw - 2em);
    height: calc(100vh - 2em);
    position: fixed;
    top: 1em;
    left: 1em;
    background-color: whitesmoke;
    background-image: repeating-linear-gradient(45deg, rgb(237, 237, 237) 0px, rgb(237, 237, 237) 92px,rgb(242, 242, 242) 92px, rgb(242, 242, 242) 184px);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }

  .hint {
    padding: .75em;
    font-size: 2.5em;
    font-weight: 700;
    text-align: center;
    margin: 1em auto;
    background-color: rgb(241, 207, 56);
    box-shadow: 10px 10px rgba(228, 210, 131, 0.712);
  }

  .back {
    padding: 1em;
    background-color: #e2e1e1;
    cursor: pointer;
    font-size: 1.2em;
    text-align: center;
    transition: .5s ease;
  }

  .back:hover {
    background-color: rgb(226, 221, 205);
  }
</style>
