<script>
    import Nav from '$lib/components/Nav.svelte';
    import Form from '$lib/components/Form.svelte';
    import NavTest from '$lib/components/NavTest.svelte';
    import Container from '$lib/components/global/Container.svelte';

    let signInForm = {
        title: 'let me know about you...',
        items: [{
            id: 'name',
            label: 'full name',
            type: 'text'
        }, {
            id: 'uname',
            label: 'username',
            type: 'text'
        }, {
            id: 'passwd',
            label: 'password',
            type: 'password'
        }],
        buttonText: 'Sign Up'
    }
</script>
<Container>
    <Nav></Nav>
    <Form widthBox="100%" form={signInForm}></Form>
</Container>

<NavTest></NavTest>