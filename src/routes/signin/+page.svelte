<script>
    import Nav from '$lib/components/Nav.svelte';
    import Form from '$lib/components/Form.svelte';
  import NavTest from '$lib/components/NavTest.svelte';
  import Container from '$lib/components/global/Container.svelte';2

    let signInForm = {
        title: 'get ready for the bussyness?',
        items: [{
            id: 'uname',
            label: 'username',
            type: 'text'
        }, {
            id: 'passwd',
            label: 'password',
            type: 'password'
        }],
        buttonText: 'Sign In'
    }
</script>
<Container>
    <Nav></Nav>
    <Form widthBox="95%" form={signInForm} justify-self="center"></Form>
</Container>

<NavTest></NavTest>
