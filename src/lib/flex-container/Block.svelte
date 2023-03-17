<script lang="ts">
    export let style: string = '';
    export let fixed;
    let className: string = '';
    export {className as class};


</script>
<div class="flex-block {className}" class:fixed {style}>
    <slot/>
</div>