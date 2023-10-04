
<style>
  .boujee-text {
  --bg-size: 400%;
  --color-one: hsl(189,100%,50%);
  --color-two: hsl(139,100%,50%);
  font-size: clamp(3rem, 25vmin, 8rem);
  background: linear-gradient(
                90deg,
                var(--color-one),
                var(--color-two),
                var(--color-one)
              ) 0 0 / var(--bg-size) 100%;
  color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
  animation: move-bg 8s infinite linear;
}

@media (prefers-reduced-motion: no-preference) {
  .boujee-text {
    animation: move-bg 8s linear infinite;
  }
  @keyframes move-bg {
    to {
      background-position: var(--bg-size) 0;
    }
  }
}
</style>
  <h1 class="boujee-text">Adasat Bonilla</h1>


Mosquito
