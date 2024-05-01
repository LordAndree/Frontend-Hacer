<script>
    export let width;
    export let color;
    export let tipeborder;
</script>

<div style="display: flex; justify-content: center;">
    <div style="display: flex; border: {tipeborder}; border-radius: 10px; width: {width}; justify-content: space-around; background: {color}">
        <div style="padding: 5% 5% 5% 5%;">
            <div style="display: flex; flex-direction: row;">
                <slot/>
            </div>
        </div>
    </div>
</div>