<script>
  import Project from "../components/Project.svelte"
</script>

<main class="bg-black text-white min-h-screen">
  <section id="home" class="py-20 px-4">
    <div class="flex justify-center items-center h-fit m-auto space-x-4">
      <!-- Added space-x-4 for spacing between images -->
      <img
        src="/src/assets/images/text.png"
        class="w-1/5 h-auto"
        alt="Logo Part 2"
      />
      <img
        src="/src/assets/images/logo.png"
        class="w-1/12 h-auto"
        alt="Logo Part 1"
      />
    </div>
  </section>

  <section id="projects" class="py-20 px-4">
    <h2 class="text-3xl font-bold mb-8">My Projects</h2>
    <Project
      title="Project 1"
      description="This is my awesome project 1"
      link="https://github.com/yourusername/project1"
    />
    <!-- Add more Project components as needed -->
  </section>

  <section id="contact" class="flex justify-around py-20 px-4">
    <h2 class="text-3xl font-bold mb-8">Contact Me</h2>
    <p class="text-lg">
      <a
        href="mailto:amilksheyke@gmail.com"
        class="text-blue-500 underline hover:text-blue-300"
        >amilksheyke@gmail.com</a
      >
    </p>
  </section>
</main>

<style>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  body {
    font-family: "Arial", sans-serif;
  }
</style>
