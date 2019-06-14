<template>
  <section class="container">
    <h1> Experts </h1>
    
    <p class="subheading"> Turn your knowledge into improvements in AI </p>

    <div class="links">
        <nuxt-link
          to="/demo"
          class="button--green">Individual</nuxt-link>
        <nuxt-link
          to="/demo"
          class="button--blue">Enterprise</nuxt-link>
        <nuxt-link
          to="/whitepaper"
          class="button--white">Whitepaper</nuxt-link>
    </div>
    <div>
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
  .button--green{
    border-width: 0.2em;
    font-weight: bold;
  }
  .button--blue {
    border-width: 0.2em;
    font-weight: bold;
  }
  .button--white {
    border-width: 0.2em;
    font-weight: bold;
  }
  .cards {
    display:grid;
    grid-template-columns: repeat(3, auto);
    column-gap: 3em;
    margin-top: 0em;
  }
  @media (max-width:800px) {
      .cards {
        display: none;
      }
      .button--green{
        font-size: 8px;
      }
      .button--blue {
        font-size: 8px;
      }
      .button--white {
        font-size: 8px;
      }
  }
  .headline {
    margin-bottom: 1em;
    font-size: 2em;
  }
  .cards li {
    transition-duration: 0.5s;
  }

  .card-content {
    margin-top: 3em;
    font-weight: bold;
    font-size: 1.2em;
    color: rgb(190, 190, 190);
  }

  .fa-7x {
    margin-top: 1em;
    color: rgb(190, 190, 190);
  }

  @media (max-width:2000px){
    .cards li {
      transform:scale(0.6);
    }
    .cards {
      margin-top: -7em;
    }
    .card-text {
      display: none;
    }
  }
  
  @media (min-width:2000px) {
    .cards li:hover {
      transform: scale(1.1);
    }
  }
</style>
