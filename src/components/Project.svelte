<script>
  export let title
  export let description
  export let link
</script>

<div class="project">
  <h3>{title}</h3>
  <p>{description}</p>
  <a href={link} target="_blank">View Project</a>
</div>

<style>
  .project {
    border: 1px solid #ccc;
    padding: 10px;
    margin: 10px 0;
  }
</style>
