
<template>
  <div>
    <div className="card">
    <h1>{{title}}</h1>
      <p> {{content}} </p>
    </div>
  </div>
</template>

<script>
export default {
    name: "CardResume",
    props: {
        title: {
            type: String,
            default: "Title",
            required: true,
        },
        content: {
            type: String,
            default: "Content",
            required: true,
        }
    },
  }

</script>



<style scoped>
  .card {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 1rem;
    margin: 1rem 0;
  }

</style>