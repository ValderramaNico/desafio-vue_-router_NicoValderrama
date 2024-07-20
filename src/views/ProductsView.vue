<template>
  <section class="products">
    <div class="container products" id="products">
      <h2 class="text-center">Nuestros Productos</h2>
      <div class="row">
        <div class="col-sm-4 col-12 px-5 mb-4">
          <Card
            :title="title"
            :subtitle="subtitle"
            :price="price"
            :quantity="quantity"
          />
        </div>
      </div>
    </div>
  </section>
  <div class="button-container">
    <router-link to="/">
      <button class="return" href="">Volver al inicio</button>
    </router-link>
  </div>
</template>

<script>
import Card from "../components/Card.vue";

export default {
  name: "ProductsView",
  components: {
    Card,
  },
  props: ["title", "subtitle", "price", "quantity"],
};
</script>

<style scoped>


.products {
  padding: 4%;
  height: 90vh;
}

h2 {
  font-size: 3.75rem;
  font-weight: 600;
  color: #707070;
}

.button-container {
  display: flex;
  justify-content: center;
  margin-bottom: 1rem;
}

.return {
  font-size: 17px;
  padding: 0.5em 2em;
  border: transparent;
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
  background: #e83e8c;
  color: white;
  border-radius: 10px;
}

.return:active {
  transform: translate(0em, 0.2em);
}
</style>
