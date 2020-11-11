<script>
  import router from "page";
  import Home from "./Pages/Home.svelte";
  import Articles from "./Pages/Articles.svelte";
  import NotFound from "./Pages/NotFound.svelte";
  import Newsletter from "./Pages/Newsletter.svelte";

  let page;

  router("/", () => (page = Home));
  router("/articles", () => (page = Articles));
  router("/newsletter", () => (page = Newsletter));
  router("/*", () => (page = NotFound));

  router.start();
</script>

<svelte:component this={page} />
