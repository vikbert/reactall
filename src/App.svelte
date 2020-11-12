<style>
  main {
    display: flex;
    flex-wrap: wrap;
    width: 100vw;
    height: 100vh;
  }
  .editor {
    width: 50vw;
    display: grid;
    place-items: center;
    outline: 1px solid yellow;
  }
</style>

<main>
  <div class="editor">
    <iframe
      src="https://codesandbox.io/embed/editor-svelte-nkx0h?fontsize=14&theme=dark"
      style="width:100%; height:100vh; border:0; border-radius: 4px; overflow:hidden;"
      title="editor-svelte"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
      sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts" />
  </div>
  <div class="editor">
    <iframe
      src="https://codesandbox.io/embed/editor-vue-1s1z8?fontsize=14&theme=dark"
      style="width:100%; height:100vh; border:0; border-radius: 4px; overflow:hidden;"
      title="editor-vue"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; hid; microphone; midi; payment; usb; vr; xr-spatial-tracking"
      sandbox="allow-forms allow-modals allow-popups allow-presentation allow-same-origin allow-scripts" />
  </div>
</main>
