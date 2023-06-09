<script lang="ts">
    export { classname as class };
    let classname = "";
    import { Button } from "figsvelte";
    let count: number = 0;
    const increment = () => {
        count += 1;
    };
</script>

<Button class={classname} on:click={increment}>
    count is {count}
</Button>
