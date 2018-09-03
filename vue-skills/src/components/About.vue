<template>
    <div class="about">
        <h1>Hello {{ their_name }}, This is about page</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus dignissimos aspernatur dolor nam placeat hic, aliquam quae provident recusandae saepe, et animi inventore eos facilis ratione quaerat non. Voluptatum, ut.</p>
    </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      their_name: this.$route.params.name
    }
  },
}
</script>

