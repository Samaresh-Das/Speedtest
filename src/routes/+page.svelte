<script>
  import image1 from '../components/image1.jpg'
  import image2 from '../components/image2.jpg'
  import logo from '../components/logo.png'
</script>
<main>
  <nav class="navbar navbar-expand-lg text-light navbar-dark" data-bs-theme="dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#top"><img src={logo} alt="" class="logo"/></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end">
        <ul class="nav ">
        <li class="nav-item">
            <a href="#top" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
          <a href="/about" class="nav-link">About Us</a>
        </li>
        <li>
          <a href="/faq" class="nav-link">Help</a>
        </li>
      </ul>
    </div>
      
    </div>
  </nav>
    <div id="middle" class='all'>
        <h1 class="heading">Speed Test</h1>
        <p>
          Download speed is most relevant for people who are consuming content on
          the Internet, and we want SPEED.com to be a very simple and fast speed
          test.
        </p>
        <img src={image1} alt="img" class="responsive"/>
        <a href="/speedtest"><button class="btn"> Take Test</button></a>
      </div>
      <div>
      </div>
</main>
<style>
  img{
    background-color: white;
  }
  ul {
    margin: 14px 3px;
    padding: 3px 17px;
    color: aliceblue;
    size: 44pt;
  }
  a {
    color: white
  }
  li a{
    border-radius: 5px;
  }
  li a:hover{
    background-color: orange;
    color: black; 
    border-radius: 5px;

  }
  nav {
    background-color: #060c59;
  }
  
  .logo {
    height: 3rem;
    width: 9rem;
  }
  h1 {
    position: relative;
    top: 20px;
    font-family: "Inika";
    font-size: 10vw;
    font-weight: 700;
    text-align: left;
    margin-left: 20px;
    display: flex;
    align-items: center;
    color: #00ffff;
  }

  p {
    position: relative;
    width: 550px;
    top: 70px;
    font-family: "Inika";
    font-size: 2.5vw;
    font-weight: 700;
    display: flex;
    margin-left: 20px;
    align-items: center;
    color: rgba(255, 255, 255, 1);
  }

  .btn {
    position: relative;
    height: 115px;
    width: 377px;
    left: 109px;
    top: 90px;
    font-size: 3vw;
    font-family: "Iceland", cursive;
    font-style: normal;
    text-align: center;
    font-weight: 400px;
    background-color: #fffefe;
    border-color: black;
    border-radius: 30px;
    color: black;
  }

  .btn:hover {
    color: red;
    background-color: orange;
    font-weight: bold;
    height: 130px;
  }

  .responsive {
    position: absolute;
    height: auto;
    width: 45%;
    right: 0;
    top: 150px;
  }
  .all {
    background: linear-gradient(135deg, #040740 0%, #03086D 100%);
    height: 900px;
  }  
</style>