<script lang="ts">
  import "./app.css";
  import * as THREE from "three";
  import * as SC from "svelte-cubed";
</script>

<main class="h-screen w-full text-yellow-300">
  <div class="h-full w-full bg-[url('./assets/background.png')] bg-cover">
    <div class="absolute -z-50">
      <!-- <SC.Canvas>
        <SC.Mesh geometry={new THREE.BoxGeometry()} />
        <SC.PerspectiveCamera position={[1, 1, 3]} />
      </SC.Canvas> -->
    </div>
    <h1>Hi I'm Weichen and I like to build cool stuff</h1>
  </div>
</main>
