<script lang="ts">
  export let appName: string
  let currentYear = new Date().getFullYear()
</script>

<footer id="app-footer">
  &copy; {appName} | Nico Web Development | {currentYear}
</footer>

<style lang="scss">
  footer {
    position: absolute;
    display: flex;
    justify-content: center;
    bottom: 0;
    width: 100%;
    padding: 0.5rem 0;
    background: #EFEFEF;
  }
</style>