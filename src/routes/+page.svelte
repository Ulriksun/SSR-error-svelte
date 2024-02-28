export const ssr = false;

<script>
    import {testDoc} from '../lib/documentTester.js'
    const name = document.URL;
</script>

<div style="display:flex; ">
    <p>hei hallo</p>
    {name}
    <button onclick={() => console.log(testDoc)}>log doc</button>
    <p>updd</p>
</div>


<style>

</style>
