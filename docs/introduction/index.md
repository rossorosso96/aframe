<a-box
  position="0 1.5 -5"
  width="10"
  height="3"
  depth="0.1"
  color="#a9a9a9"
  material="roughness: 1; metalness: 0;"
></a-box>
<!-- parete posteriore -->
<a-box
  position="-5 1.5 0"
  width="0.1"
  height="3"
  depth="10"
  color="#a9a9a9"
></a-box>
<!-- parete sinistra -->
<a-box
  position="5 1.5 0"
  width="0.1"
  height="3"
  depth="10"
  color="#a9a9a9"
></a-box>
<!-- parete destra -->
<a-box
  position="0 3 0"
  width="10"
  height="0.1"
  depth="10"
  color="#aaaaaa"
></a-box>
<!-- soffitto piatto -->
<a-box
  position="0 1.2 -5.01"
  width="4"
  height="0.05"
  depth="0.01"
  color="#ffd700"
  emissive="#ffd700"
></a-box>
<a-box
  position="0 0.1 0"
  width="2"
  height="0.2"
  depth="2"
  color="#888"
  material="roughness: 1;"
></a-box>
<a-plane
  position="0 1.5 -4.9"
  width="2"
  height="2.5"
  rotation="0 0 0"
  material="transparent: true; opacity: 0.3; color: #ccccff"
></a-plane>
<!-- Stanza 1 -->
<a-box
  position="0 1.5 -5"
  width="10"
  height="3"
  depth="10"
  color="#aaa"
  material="roughness: 1;"
></a-box>

<!-- Corridoio -->
<a-box position="0 1.5 -11" width="3" height="3" depth="2" color="#bbb"></a-box>

<!-- Stanza 2 -->
<a-box position="0 1.5 -16" width="8" height="3" depth="8" color="#ccc"></a-box>
<a-light
  type="directional"
  intensity="0.3"
  position="2 4 2"
  castShadow="true"
></a-light>
<a-light type="ambient" intensity="0.4"></a-light>
<a-entity position="0 1.6 5">
  <a-camera wasd-controls="acceleration: 20" look-controls>
    <a-cursor></a-cursor>
  </a-camera>
</a-entity>
