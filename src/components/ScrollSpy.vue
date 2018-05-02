<template>
  <div>
    <nav class="navbar is-info is-fixed-top">
      <div class="container">
        <div class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item" href="#one" id="link-one" v-bind:class="{ menuSelected: selected[0] === true }">One</a>
          <a class="navbar-item" href="#two"  id="link-two" v-bind:class="{ menuSelected: selected[1] === true }">Two</a>
          <a class="navbar-item" href="#three" id="link-three" v-bind:class="{ menuSelected: selected[2] === true }">Three</a>
          <a class="navbar-item" href="#four" id="link-four" v-bind:class="{ menuSelected: selected[3] === true }">Four</a>
          <a class="navbar-item" href="#five" id="link-five" v-bind:class="{ menuSelected: selected[4] === true }">Five</a>
          <a class="navbar-item" href="#six" id="link-six" v-bind:class="{ menuSelected: selected[5] === true }">Six</a>
        </div>
        </div>
      </div>
    </nav>

    <!-- TEXT SECTION -->
    <section class="section">
      <div class="container">
        <h1 class="title">The List</h1>

        <div class="block content">
          <h2 class="title" id="one">One</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>


        <div class="block content">
          <h2 class="title" id="two">Two</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>

        <div class="block content">
          <h2 class="title" id="three">Three</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>

        <div class="block content">
          <h2 class="title" id="four">Four</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>

        <div class="block content">
          <h2 class="title" id="five">Five</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>

        <div class="block content">
          <h2 class="title" id="six">Six</h2>
          <p>Lorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
          <h3>Sub Chakra</h3>
          <p>glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouwsLorem ipsum sit dolor aset glouws</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "ScrollSpy",
  props: {},
  data: function() {
    return {
      selected: [false, false, false, false, false, false]
    };
  },
  methods: {
    handleScroll() {
      const els = document.querySelectorAll("div.block");
      els.forEach((el, i) => {
        const elTop = el.getBoundingClientRect().top;
        const elBottom = el.getBoundingClientRect().bottom;
        if (elTop <= 60 && elBottom >= 0) {
          this.selected.splice(i, 1, true);
        }
        if (elTop >= 60 || elBottom <= 0) {
          this.selected.splice(i, 1, false);
        }
        console.log(i, elTop, elBottom);
      });
    }
  },
  created: function() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed: function() {
    window.removeEventListener("scroll", this.handleScroll);
  }
};
</script>


<style scoped>
.menuSelected {
  background: #0000ff;
}
</style>
