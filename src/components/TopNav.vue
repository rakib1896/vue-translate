<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>
      <div class="media-body d-lg-block">
        <b-button
          class="mx-1 text-white"
          variant="success"
          size="sm"
          v-b-modal.translate-modal
        >
          Translate
        </b-button>
      </div>
    </b-navbar>
    <translate-modal></translate-modal>
  </div>
</template>

<script>
import TranslateModal from "./TranslateModal";
export default {
  name: "TopNav",
  components: { TranslateModal },
};
</script>
