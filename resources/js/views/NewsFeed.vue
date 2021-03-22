<template>
    <div class="flex flex-col items-center py-4">
        <NewPost></NewPost>
        <Post v-for="post in posts.data" :post="post" :key='post.data.post_id'></Post>
    </div>
</template>

<script>
import NewPost from '../components/NewPost';
import Post from '../components/Post';

    export default {
       name: 'NewsFeed',
       components: {
           NewPost,
           Post
        },

        data: () => {
            return {
                posts: null,
            }
        },

        mounted() {
            axios.get('/api/posts')
            .then(res => {
                this.posts = res.data;
            })
            .catch(err => {
                console.log(err);
            })
        }
    }
</script>

<style scoped>

</style>
