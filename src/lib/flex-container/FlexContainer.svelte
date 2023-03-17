<script lang="ts">
    export let style:string = '';
    let className: string = '';
    export let horizontal;
    export {className as class }
</script>
<div class="tsui-flex-container {className}" class:horizontal style="{style}">
    <slot/>
</div>