<script>
  let dateNow = new Date().getTime();
  let dateEnd = new Date('2020-05-25').getTime();
  let diff =  dateEnd - dateNow;
  let date = Math.round(diff/(1000*60*60*24));
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
  :global(*) {
    box-sizing: border-box
  }
  :global(body, div) {
    font-family: 'Pacifico', cursive;
    margin: 0;
    padding-top: 90px;
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
    top:0;
    color: #f1f1f1;
    width: 100%;
    background: rgba(118, 64, 139, 0.6)
  }
  .App-container {
    display: grid;
    grid-template-columns: minmax(auto,1280px);
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
    font-size: 45px;
    margin: 0;
    padding: 0;
    letter-spacing: 2px;
    text-shadow: 6px 6px 0px rgba(0,0,0,0.2)
  }
  p {
    font-size: 40px;
    margin: 0;
    padding: 0;
    letter-spacing: 1.2px;
    text-shadow: 3px 3px 0px rgba(0,0,0,0.1);
  }
  figure {
    margin: 0;
    padding:0;
    text-align: right;
  }
</style>

<video autoplay muted loop id="myVideo">
  <source src="https://instagram.fnva1-1.fna.fbcdn.net/v/t50.2886-16/79791435_579264762876155_2111269559389555774_n.mp4?efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIiwicWVfZ3JvdXBzIjoiW1wiaWdfd2ViX2RlbGl2ZXJ5X3Z0c19vdGZcIl0ifQ&_nc_ht=instagram.fnva1-1.fna.fbcdn.net&_nc_cat=111&_nc_ohc=pfLk2EldiPwAX8myuyp&vs=17868557554554223_4227504090&_nc_vs=HBksFQAYJEdFdUZ3UVQ3RUd5VzFnNENBRDZNZ25CNnZFd2Ria1lMQUFBRhUAAsgBABUAGCRHTS1YeUFTTVNIeEIzOGtCQU9jZU5JSXRCejQ5YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMBUAABgAFt6Kr%2Br31r0%2FFQIoAkMzLBdAI7tkWhysCBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_rid=73ce7c75ce&oe=5EC26B7D&oh=a35ccb17731e1f479dee681b5c2dce5a" type="video/mp4">
</video>

<div class="App">
  <div class="App-container">
    <div class="App-content">
      <div class="App-title">
        <h1>The video that changes everything</h1>
        <p>Days to end quarantine: {date}</p>
      </div>
      <div class="App-image">
        <figure>
          <img src="https://cdn130.picsart.com/290937723004211.png" alt="">
        </figure>
      </div>
    </div>
  </div>
</div>