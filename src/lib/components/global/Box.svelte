<script>
    export let width;
    export let color;
</script>

<div class="card" style="display: flex; justify-content: center;">
    <div style="display: flex; border-radius: 10px; width: {width}; justify-content: space-around; background: {color}">
        <div style="padding: 5% 5% 5% 5%;">
            <div style="display: flex; flex-direction: row;">
                <slot/>
            </div>
        </div>
    </div>
</div>