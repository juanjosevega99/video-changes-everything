<script>
  let dateNow = new Date().getTime();
  let dateEnd = new Date('2020-05-25').getTime();
</script>

<style>
  /* @import url(''); */
  :global(*) {
    box-sizing: border-box;
  }
  :global(body, div) {
    margin: 0;
    padding: 0;
  }
  #myVideo {
    position: fixed;
    right: 0;
    bottom: 0;
    min-width: 100%;
    min-height: 100%;
  }
  .App {
    position: absolute;
    bottom: 0;
    top: 0;
    color: #f1f1f1;
    width: 100%;
    background: rgba(red, green, blue, alpha);
  }
  .App-container {
    display: grid;
    grid-template-columns: minmax(auto, 1280px);
    justify-content: center;
    align-items: center;
  }
  .App-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
  }
  .App img {
    width: 80%;
    height: auto;
  }

  .App-title {
    padding: 1em;
  }

  h1 {
    color: white;
    font-size: 50px;
    margin: 0;
    padding: 0;
    letter-spacing: 2px;
    text-shadow: 6px 6px 0px rgba(0, 0, 0, 0.2);
  }

  p {

  }

  figure {
    margin: 0;
    padding: 0;
  }
</style>

<video autoplay muted loop id="myVideo">
  <source src="https://instagram.fnva1-1.fna.fbcdn.net/v/t51.2885-15/e35/72661532_162861384957817_6944310968540763528_n.jpg?_nc_ht=instagram.fnva1-1.fna.fbcdn.net&_nc_cat=101&_nc_ohc=uqrHvmvUHsgAX97roAx&oh=a42ca2d88c91c3d5ea886a92567d51b4&oe=5EBE5E81" type="video/mp4">
</video>

<div class="App">
  <div class="App-container">
    <div class="App-content">
      <div class="App-title">
        <h1>xd</h1>
        <p>days</p>
      </div>
    </div>
  </div>
</div>