<template lang="pug">
    <div>
        <h1>Contact Us</h1>
        <p>
            <ul>
                <li>Email: {{ email }}</li>
                <li>Website: {{ web }}</li>
            </ul>
        </p>
    </div>
</template>

<script>
export default {
    name: 'Contact',
    data(){
        return {
            email: 'kclownstroupe@gmail.com'
        }
    }
}
</script>