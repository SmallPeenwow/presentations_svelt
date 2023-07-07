<script lang="ts">
    import Slide from "./slide.svelte";
</script>

<Slide animate>
    <div class="text-green-700">Auto-Animate</div>
</Slide>

<Slide animate>
    <div class="text-red-600 mt-8">Auto-Animate</div>
</Slide>

<Slide>
    Horizontal Slide
</Slide>

<Slide>
    <Slide>Vertical slide 1</Slide>
    <Slide>Vertical slide 2</Slide>
</Slide>