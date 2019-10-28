<template>

  <section >
    <div class="parallax-title">
      <div>
        <img src="../assets/images/biglogo.png" class="biglogo">
      </div>
      <h1> Data Science For Domain Experts </h1>

      <div class="links">
          <a
            href="https://reasoned.us20.list-manage.com/subscribe/post?u=cf65772f893ac97470fb3ae81&id=ec94e66734"
            class="button--green">Individual</a>
          <a
            href="https://reasoned.us20.list-manage.com/subscribe/post?u=cf65772f893ac97470fb3ae81&id=ec94e66734"
            class="button--blue">Enterprise</a>
          <a
            href="https://docs.google.com/document/d/1d8IH734g_bwnHXLvTe24OXdm97ioIqnUuMTwmAbtUSM/edit?usp=sharing"
            class="button--yellow">Yellowpaper</a>
      </div>
      <!-- Begin Mailchimp Signup Form -->
      <link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">
      <div id="mc_embed_signup">
      <form action="https://reasoned.us20.list-manage.com/subscribe/post?u=cf65772f893ac97470fb3ae81&amp;id=ec94e66734"
            method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form"
            class="validate" target="_blank" novalidate>
          <div id="mc_embed_signup_scroll">
            <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
            <div style="position: absolute; left: -5000px;" aria-hidden="true">
              <input type="text" name="b_cf65772f893ac97470fb3ae81_ec94e66734" tabindex="-1" value="">
            </div>
            <div class="clear">
              <input type="submit" value="Keep me posted" name="subscribe" id="mc-embedded-subscribe" class="button">
            </div>
          </div>
      </form>
      </div>
      <!--End mc_embed_signup-->
      <div class="cards-d">
        <ul class="cards">
          <li>
            <font-awesome-layers full-width class="fa-6x">
              <font-awesome-icon icon="vials"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Assisted Data Science</h3>
                <div class="card-text">
                  <div> GUI to assist you to explore </div>
                  <div> and invent new knowledge </div>
                  <div> &nbsp; </div>
                </div>
              </div>
            </v-card-title>
          </li>
          <li>
            <font-awesome-layers full-width class="fa-6x">
              <font-awesome-icon icon="search"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Neural Logic Reasoning</h3>
                <div class="card-text">
                  <div> Reason through logic </div>
                  <div> but compute with neural networks </div>
                  <div> &nbsp; </div>
                </div>
              </div>
            </v-card-title>
          </li>
          <!--
          <li>
            <font-awesome-layers full-width class="fa-6x">
              <font-awesome-icon icon="user-lock"/>
            </font-awesome-layers>
            <v-card-title primary-title class="card-content">
              <div>
                <h3 class="headline mb-0">Decentralized Community</h3>
                <div class="card-text">
                <div> Claim the ownership of the knowledge</div>
                <div> then share it with the world </div>
                </div>
              </div>
            </v-card-title>
          </li>
          -->
        </ul>
      </div>
      <div class="footer">
        <p>&copy; 2019 All Rights Reserved | Los Altos CA USA 94024</p>
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
    color: rgb(190, 190, 190);
  }
  .cards {
    display:grid;
    grid-template-columns: repeat(2, auto);
    column-gap: 0;
    margin-top: 0;
  }

  .biglogo {
    display: none;
  }

  h1 {
      margin-top: 10em;
      margin-bottom: 2em;
      font-size: 3em;
      color: white;
  }

  #mc_embed_signup {
      font-size: 1em;
      margin-top: 3em;
      margin-bottom: 3em;
      text-transform: capitalize;
      font-weight: bold;
  }

  #mc-embedded-subscribe {
    font-weight: bold;
  }

  .headline {
    margin-bottom: 1em;
    font-size: 1.5em;
  }
  .cards li {
    transition-duration: 0.5s;
  }

  .cards li:hover {
    transform: scale(1.1);
  }

  .card-content {
    margin-top: 1em;
    margin-bottom: 10em;
    font-size: 1.3em;
    color: rgb(190, 190, 190);
  }

  .fa-6x {
    margin-top: 3em;
    margin-bottom: 0.2em;
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
    border: 2px solid #03d6a5;
    font-weight: bold;
    color: #03d6a5;
    text-decoration: none;
    padding: 0.6em 2em;
    margin-left: 0;
    transition-duration: 0.5s;
  }

  .button--green:hover {
    color: #fff;
    background-color: #3b8070;
  }

  .button--blue {
    display: inline-block;
    border-radius: 4px;
    border: 2px solid #04aada;
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
  }

  .button--yellow {
    display: inline-block;
    border-radius: 4px;
    border: 2px solid rgb(210, 170, 0);
    font-weight: bold;
    color: rgb(210, 170, 0);
    text-decoration: none;
    padding: 0.6em 2em;
    margin-left: 1em;
    transition-duration: 0.5s;
  }

  .button--yellow:hover {
    color: #fff;
    background-color: rgb(120, 100, 0);
  }

  .cards-d {
    margin-left: 25%;
    margin-right: 25%;
  }

  @media (max-width:800px) {
    h1 {
      margin-top: 1em;
      margin-bottom: 2em;
      font-size: 2em;
      color: white;
    }

    #mc_embed_signup {
      margin-top: 0;
    }

    .links {
      padding-bottom: 5em;
    }
    .cards-d {
      margin: 1em 0;
      background-color: black;
    }

    .cards {
      display:block;
      background-color: black;
    }

    .fa-6x {
      margin-left: -0.6em;
      margin-top: 0.5em;
      margin-bottom: 0;
    }

    .card-content {
      margin-left: -2em;
      margin-bottom: 1em;
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
      margin-left: 0;
    }
    .button--blue {
      color: #fff;
      background-color: #35495e;
      margin-left: 0;
    }
    .button--yellow {
      color: #fff;
      background-color:  rgb(120, 100, 0);
      margin-left: 0;
    }
  }

  @media (min-width:800px) {
    .parallax-title {
      top: 5%;
      left: 2%;
      right: 2%;
    }
  }

  @media (max-width:2000px) and (min-width: 800px){
    h1 {
      margin-top: 5em;
      margin-bottom: 2em;
      font-size: 2em;
      color: white;
    }

    #mc_embed_signup {
      margin-top: 2em;
    }

    .cards-d {
      margin-top: 1em;
      margin-left: 20%;
      margin-right: 25%;
    }
    .fa-6x {
      margin-left: -0.6em;
      margin-top: 0.5em;
      margin-bottom: 0;
    }

    .card-content {
      margin-left: -2em;
      margin-bottom: 1em;
    }
  }

/*  @media (min-width:1900px) {
    .parallax-title {
      top: 10%;
    }
  }



  @media (min-width:1900px) {
    .cards li:hover {
      transform: scale(1.17);
    }
    .footer {
      padding-top: 5em;
    }
  }
*/
</style>
