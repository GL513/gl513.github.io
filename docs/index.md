---
hide:
  - footer
---

<style>
  .rotate {
  animation: rotation 10s infinite linear;
}

@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(359deg);
  }
}
</style>

<style>
big {
  font-size: 32px;
}
</style>
<big>
<p align="center">Welcome to the GL513 Github Pages.</p>
</big>
<p align="center">
  <img src="/images/glLogo.png" onload="imgresize(this); height="500" width="500" class="rotate"/>
</p>

<script src='https://cdn.jsdelivr.net/npm/@widgetbot/crate@3' async defer>
    new Crate({
        server: '1069035855181787199', // GL513.
        channel: '1069035969195544656', // #rules
        color: '#ff6400'
        })

      crate.notify({
  content: 'Hello!',
  timeout: 5000,
  avatar: 'images/glLogo.png'
})
</script>




