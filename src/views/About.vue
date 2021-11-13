<template>
  <body>
    <!-- 
        To Generate With Emmet: 
        section*8>(h1>{Nice Curves!})+p>lorem   then hit tab
    -->
    <div class="overflow-hidden">
      <section class="white">
        <v-row>
          <div>
            <h1>Mindful Data. Artful Design.</h1>
          </div>
        </v-row>
      </section>
      <section class="dark">
        <h1>Tech Stack</h1>
        <p>
          Id itaque corporis asperiores consectetur beatae? Consequuntur maiores
          voluptates ducimus assumenda odio velit enim sed ipsam, natus minima
          repellendus eum. Vero cupiditate exercitationem doloribus earum eius
          sapiente non sit atque.
        </p>
      </section>
      <section class="red">
        <h1>Design Philosophy</h1>
        <p>
          Est totam dolores cumque deserunt doloribus aliquid quaerat eius ab,
          perferendis ipsam soluta consectetur obcaecati dolore reprehenderit
          quos aut voluptatibus porro ex at aliquam vero beatae. Dignissimos
          nemo amet harum.
        </p>
      </section>
      <section class="dark">
        <h1>More</h1>
        <p>
          Odit, perspiciatis eaque fugit qui quia error repellat alias! Repellat
          quisquam aliquam illo minus saepe quis vitae, consequuntur corrupti
          voluptatum accusamus explicabo voluptatibus illum modi maxime? Ullam
          reiciendis ipsum voluptatem?
        </p>
      </section>
      <section class="pink">
        <h1>More</h1>
        <p>
          In magnam reprehenderit ea laborum facere, qui illum obcaecati
          pariatur sed, provident ducimus eos blanditiis repellendus officia
          atque vitae odit distinctio laudantium cum sequi temporibus libero
          cumque! Vel, sed adipisci.
        </p>
      </section>
      <section class="dark">
        <h1>More</h1>
        <p>
          Facilis amet nostrum, optio doloremque quasi molestias esse omnis
          accusamus ullam animi enim consequatur ducimus, cum illum incidunt
          adipisci rem dolorem provident, tempore corrupti pariatur odit ea.
          Fugit, impedit consequuntur!
        </p>
      </section>
      <section class="green">
        <h1>More</h1>
        <p>
          Hic eligendi animi obcaecati repellat voluptatem id sequi, itaque
          repellendus neque alias quos illum aut nulla. Enim inventore
          exercitationem et ipsam, ipsa sit natus tenetur, cumque error tempora
          suscipit repellat?
        </p>
      </section>
      <section class="dark">
        <h1>More</h1>
        <p>
          Libero fuga quo ut officiis error labore eius dolorum in delectus
          dolore repellat doloribus debitis accusantium sunt omnis nesciunt
          neque consequuntur ratione amet facilis animi, laboriosam odio
          impedit. Ipsum, voluptate.
        </p>
      </section>
    </div>
  </body>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {
    created() {
      setTimeout(() => (this.showTitle = true), 5);
    },
  },
};
</script>

<style lang="scss">
html,
body {
  margin: 0;
  height: 100%;
}

.fade-enter-from {
  opacity: 0;
}
.fade-enter-to {
  opacity: 1;
}
.fade-enter-active {
  transition: all 2s ease;
}
.fade-leave-from {
  opacity: 1;
}
.fade-leave-to {
  opacity: 0;
}
.fade-leave-active {
  transition: all 2s ease;
}

section {
  margin: 0;
  color: blanchedalmond;
  background: #020f18;
  position: relative;
  display: flex;

  align-items: center;
  min-height: 100vh;
  padding: 100px;
}

/* utility classes */
.white {
  background: #fdfeff;
  color: #020f18;
}
.red {
  background: #df3a3a;
}
.pink {
  background: #ee2dd4;
}
.green {
  background: #b0e767;
}
.dark {
  background: #0a0a0a;
}
</style>
