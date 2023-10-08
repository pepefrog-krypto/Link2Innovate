<!--Handle.svelte-->

<script>
export let nombre = "";


function handle (e){
    const target = e.target;
    nombre = e.target.value;
}
    
</script>