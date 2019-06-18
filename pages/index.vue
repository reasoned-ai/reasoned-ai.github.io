<template>

  <section >
    <div class="parallax-title">
      <div>
        <img src="../assets/images/biglogo.png" class="biglogo">
      </div>
      <h1> Experts </h1>
      
      <p class="subheading"> Turn your knowledge into improvements in AI </p>

      <div class="links">
          <nuxt-link
            to="/demo"
            class="button--green">Individual</nuxt-link>
          <nuxt-link
            to="/signup"
            class="button--blue">Enterprise</nuxt-link>
          <nuxt-link
            to="/whitepaper"
            class="button--white">Whitepaper</nuxt-link>
      </div>
      <p class="comingsoon"> Coming soon </p>

      <div class="cards-d">
        <ul class="cards">
          <li>
            <font-awesome-layers full-width class="fa-7x">
              <font-awesome-icon icon="vials"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Guided Data Science</h3>
                <div class="card-text">
                <div> Intelligent GUI to help you explore data </div>
                <div> and experiment ideas. </div> 
                <div> No knowledge of neural networks is </div>
                <div> required.</div>
                </div>
              </div>
            </v-card-title>
          </li>
          <li>
            <font-awesome-layers full-width class="fa-7x">
              <font-awesome-icon icon="book-reader"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Logic Reasoning</h3>
                <div class="card-text">
                <div> AI explains itself in human logic. </div>
                <div> You can confirm or correct in human logic too. </div> 
                <div> Warning: </div>
                <div> AI might challenge with counter-examples. </div>
                </div>
              </div>
            </v-card-title>
          </li>
          <li>
            <font-awesome-layers full-width class="fa-7x">
              <font-awesome-icon icon="search-dollar"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Decentralized Community</h3>
                <div class="card-text">
                <div> The improvement due to your efforts will be recorded</div>
                <div> securely and shared among your peers. </div>
                <div> Let's create a sustainable knowledge economy </div>
                <div> together.</div>
                </div>
              </div>
            </v-card-title>
          </li>
        </ul>
      </div>
      <div class="footer">
        <p>&copy; 2019 All Rights Reserved | Los Altos CA USA</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style>
  .links {
    padding-top: 1em;
  }
  .footer {
    display: block;
    padding-top: 1em;
    color: rgb(190, 190, 190)
  }
  .cards {
    display:grid;
    grid-template-columns: repeat(3, auto);
    column-gap: 3em;
    margin-top: 0em;
  }

  .biglogo {
    display: none;
  }

  h1 {
      margin-top: 0.75em;
      font-size: 5em;
      text-transform: uppercase;
      color: white;
  }

  .subheading {
      font-size: 2.5em;
      margin-top: 0.5em;
      margin-bottom: 0.5em;
      text-transform: capitalize;
      color: rgb(190, 190, 190);
      font-weight: bold;
  }
  .comingsoon {
      font-size: 1.5em;
      margin-top: 1.5em;
      text-transform: capitalize;
      font-weight: bold;
  }
  .headline {
    margin-bottom: 1em;
    font-size: 2em;
  }
  .cards li {
    transition-duration: 0.5s;
  }

  .card-content {
    margin-top: 1em;
    font-weight: bold;
    font-size: 1.2em;
    color: rgb(190, 190, 190);
  }

  .fa-7x {
    margin-top: 1em;
    color: rgb(190, 190, 190);
  }

  .parallax-title {
    position: absolute;
    top: 15%;
    background: rgba(0, 0, 0, 0);
    color: white;
    text-align: center;
  }
  
  .button--green {
    display: inline-block;
    border-radius: 4px;
    border: 1px solid #03d6a5;
    border-width: 0.2em;
    font-weight: bold;
    color: #03d6a5;
    text-decoration: none;
    padding: 0.6em 2em;
    margin-left: 1em;
    transition-duration: 0.5s;
  }

  .button--green:hover {
    color: #fff;
    background-color: #3b8070;
    transform: scale(1.1);
  }

  .button--blue {
    display: inline-block;
    border-radius: 4px;
    border: 1px solid #04aada;
    border-width: 0.2em;
    font-weight: bold;
    color: #04aada;
    text-decoration: none;
    padding: 0.6em 2em;
    margin-left: 1em;
    transition-duration: 0.5s;
  }

  .button--blue:hover {
    color: #fff;
    background-color: #35495e;
    transform: scale(1.1);
  }

  .button--white {
    display: inline-block;
    border-radius: 4px;
    border: 1px solid rgb(210, 210, 210);
    border-width: 0.2em;
    font-weight: bold;
    color: rgb(210, 210, 210);
    text-decoration: none;
    padding: 0.6em 2em;
    margin-left: 1em;
    transition-duration: 0.5s;
  }

  .button--white:hover {
    color: #fff;
    background-color: rgb(110, 110, 110);
    transform: scale(1.1);
  }

  .cards-d {
    margin-left: 5%;
    margin-right: 5%;
  }
  @media (max-width:800px) {
    .links {
      padding-bottom: 5em;
    }
    .cards-d {
      margin: 0;
      background-color: black;
    }
    .cards {
      display:block;
      margin-top: 2em;
      background-color: black;
    }

    .fa-7x {
      margin-left: -0.6em;
    }

    .card-content {
      margin-left: -2em;
    }

    .biglogo {
      display: inline;
    }
    .parallax-title {
      top: 15%;
    }
    .button--green {
      color: #fff;
      background-color: #3b8070;
    }
    .button--blue {
      color: #fff;
      background-color: #35495e;
    }    
    .button--white {
      color: #fff;
      background-color: rgb(110, 110, 110);
      margin-top: 1em;
    }

    .comingsoon {
      margin-top:1.5em;
      position: relative;
      transform:translateY(-3em);
    }
  }

  @media (min-width:800px) {
    .parallax-title {
      top: 5%;
      left: 2%;
      right: 2%;
    }
  }

  @media (min-width:2000px) {
    .parallax-title {
      top: 10%;
    }
  }


  @media (max-width:2000px){
    .cards li {
      transform:scale(0.6);
    }
    .cards {
      margin-top: -7em;
    }
  }
  
  @media (min-width:2000px) {
    .cards li:hover {
      transform: scale(1.17);
    }
    .footer {
      padding-top: 5em;
    }
  }

</style>
