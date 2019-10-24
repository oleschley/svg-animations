<style lang="scss">

.canvas {
    // Placement in container
    grid-column: content-start / content-end;

    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-gap: 10rem;
}

.box {
    height: 30rem;
    border: .1rem solid hsl(0, 0, 50);
    border-radius: .2rem;
}

</style>


<div class="canvas">
    <div class="box box-1">Box 1</div>
    <div class="box box-2">Box 2</div>
    <div class="box box-3">Box 3</div>
    <div class="box box-4">Box 4</div>
</div>