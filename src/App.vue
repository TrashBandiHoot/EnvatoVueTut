<template>
    <p>simple text</p>
</template>

<script>
import PageViewer from './components/PageViewer.vue';
import Navbar from './components/Navbar.vue';


export default {
    components: {
        PageViewer,
        Navbar
    },
    data() {
        return {
            activePage: 0,
            pages: [
                {
                    link: {text: 'Home', url: 'home.html'},
                    pageTitle: 'Home Page',
                    content: 'This is the home content'
                },
                {
                    link: {text: 'Projects', url: 'projects.html'},
                    pageTitle: 'Projects Page',
                    content: 'This is the project content'
                },
                {
                    link: {text: 'About', url: 'about.html'},
                    pageTitle: 'About Page',
                    content: 'This is the about content'
                }
            ]
        };
    },
}
</script>