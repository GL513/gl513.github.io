---
hide:
  - footer
---

<style>
.rotate {
  width: 100%;
  height: 100%;
  animation: spin 2s linear infinite;
}

.container {
  margin:0px;
  display: inline-block;
  transition:7s all;
}

.rotate:hover {
  transform: rotate(2000deg);
}

@keyframes spin {
  100% {
    transform: rotate(360deg);
  }
}
</style>
<big>
<p align="center">Welcome to the GL513 Github Pages.</p>
</big>
<div class="container">
<img src="/images/glLogo.png" alt="My Logo! :D"/>
</div>

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




