<template>
  <PopularMovies />
  <TopMovies />
  <UpcomingMovies />
</template>

<script>
import PopularMovies from "@/components/PopularMovies.vue";
import TopMovies from "@/components/TopMovies.vue";
import UpcomingMovies from "@/components/UpcomingMovies.vue";

export default {
  name: "Home",
  components: {
    PopularMovies,
    TopMovies,
    UpcomingMovies,
  },
};
</script>
