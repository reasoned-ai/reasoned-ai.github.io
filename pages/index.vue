<template>
  <section class="container">
    <h1> Experts : </h1>
    
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
              <div> Intelligent GUI to help you explore data </div>
              <div> and experiment ideas. </div> 
              <div> No knowledge of neural networks is </div>
              <div> required.</div>
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
              <div> AI explains itself in human logic. </div>
              <div> You can confirm or correct in human logic too. </div> 
              <div> Warning: </div>
              <div> AI might challenge with counter-examples. </div>
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
              <div> The improvement due to your efforts will be recorded</div>
              <div> securely and shared among your peers. </div>
              <div> Let's create a sustainable knowledge economy </div>
              <div> together.</div>
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
    padding-top: 15px;
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
    margin-top: 3em;
  }
  .headline {
    margin-bottom: 1em;
    font-size: 2em;
  }
  .cards li {
    transition-duration: 0.5s;
  }
  .cards li:hover {
    transform: scale(1.1);
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
</style>
