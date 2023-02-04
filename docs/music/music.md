# Music

### Comfortable Noise[^1]

<iframe id="sc-widget" src="https://w.soundcloud.com/player/?url=https://api.soundcloud.com/users/1025514118" width="100%" height="400px" scrolling="yes" frameborder="no"></iframe>
<script src="https://w.soundcloud.com/player/api.js" type="text/javascript"></script>
<script type="text/javascript">
  (function(){
    var widgetIframe = document.getElementById('sc-widget'),
        widget       = SC.Widget(widgetIframe);

    widget.bind(SC.Widget.Events.READY, function() {
      widget.bind(SC.Widget.Events.PLAY, function() {
        // get information about currently playing sound
        widget.getCurrentSound(function(currentSound) {
          console.log('sound ' + currentSound.get('') + 'began to play');
        });
      });
      // get current level of volume
      widget.getVolume(function(volume) {
        console.log('current volume value is ' + volume);
      });
      // set new volume level
      widget.setVolume(50);
      // get the value of the current position
    });

  }());
</script>
[^1]: Sorry for Light Mode!
[^2]: BandCamp Coming Soon!
