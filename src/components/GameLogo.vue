<template>
  <div class="game-logo">
    <picture>
      <source srcset="@/assets/snake.webp" type="image/webp" />
      <source srcset="@/assets/snake.png" type="image/png" />
      <img
        class="game-logo-img"
        src="@/assets/snake.png"
        alt="Snake Logo"
      />
    </picture>
    <div class="game-logo-text">
      <h1 class="game-logo-title">Snake</h1>
      <h2 class="game-logo-subtitle">Smaczna kolacja!</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "GameLogo",
};
</script>

<style>
.game-logo {
  display: flex;
  align-items: center;
  gap: 2rem;
}
.game-logo-img {
  display: block;
  width: 6rem;
}
.game-logo-text {
  line-height: 1.2;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.game-logo-title {
  font-size: 3rem;
  font-weight: 800;
  color: var(--col-prim);
}
.game-logo-subtitle {
  font-size: 1.4rem;
  font-weight: 600;
  color: var(--col-txt-sec);
}
</style>
