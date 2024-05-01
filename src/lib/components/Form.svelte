<script>
    import Box from '$lib/components/global/Box.svelte';
    import FormImage from '$lib/images/form.jpg';

    export let form = {
        title: '',
        items: [{
            label: '',
            id: '',
            type: ''

        }],
        buttonText: ''
    };

    export let widthBox;
    
</script>

<Box width={widthBox} color="#FFFFFF">
    <div style="display: flex; justify-content: space-around;">
        <div style="max-width: 600px; max-height: 350px; text-align: center;">
            <img src={FormImage} alt="do" width="100%" height="100%">
        </div>
        <Box width=100% color="#E2E7FA">
            <div style="display: flex; flex-direction: column;">
                <h1>{form.title}</h1>
                {#each form.items as i}
                    <label for={i.id}>{i.label}:</label>
                    <input style="border-radius: 10px; height: 44px; border: none;" type={i.type} id={i.id} name={i.id}><br>
                {/each}
                <div style="display: flex; justify-content: flex-end;">
                    <button type="button" style="width: 129px; height: 44px; border-radius: 10px; background-color: #ffffff; border: none;">{form.buttonText}</button>
                </div>
            </div>
        </Box>
    </div>
</Box>