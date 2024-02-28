<script>
    // import Pusher from 'pusher-js'
    // import {get_appname} from '$lib/appname.js'
    import {setContext} from 'svelte'
    export const ssr = false;

    let {
        // data,
        children,
    } = $props();

    // const pusher = new Pusher('debff950161c2b0647cb', {
    //     // auth endpoints can be configured here
    //     // userAutentication: {
    //     //     endpoint: '/pusher/auth'
    //     // },
    //     cluster: 'eu',
    // })
    // setContext('pusher', pusher)

    // pusher.bind('pusher:signin_success', function({user_data}) {
    //     console.log('fromlayout..pusher:signin_success', user_data)
    //     // puser = JSON.parse(user_data)
    //     // user_name = puser.user_info.name
    //     // const names = user_name.split(' ')
    //     // initials = [names[0][0], names.slice(-1)[0][0]].join('')
    // })
    //
    // pusher.signin()

</script>

{@render children()}
