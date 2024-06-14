<template>
  <div class="p-10 h-[100vh] bg-color overflow-auto">
    <h1 class="text-4xl text-white font-bold flex items-center mb-10">
      Trello Board
    </h1>
    <TrelloBoard />
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap");

.bg-color {
  background: linear-gradient(to right, #090e35, #22062e);
}

.league-spartan {
  font-family: "League Spartan", sans-serif;
}
</style>
