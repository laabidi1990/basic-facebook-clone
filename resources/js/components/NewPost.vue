<template>
    <div class="bg-white rounded shadow w-2/3 p-4 flex justify-between items-center">
        <div class="w-8">
            <img src="https://img-0.journaldunet.com/M0Rry_97U_EnJy_IGrIeoxkRFUY=/1280x/smart/7cfa455788b7461ea1782b0b72e31c8f/ccmcms-jdn/2383369.jpg"
            alt="profile image for user" class="w-8 h-8 object-cover rounded-full">
        </div>
        <div class="flex-1 mx-4">
            <input type="text" name="body" class="w-full pl-4 h-8 bg-gray-200 rounded-full focus:outline-none focus:ring-2 focus:ring-blue-400 text-sm" placeholder="Add a post">
        </div>
        <div>
            <button class="flex justify-center items-center rounded-full w-10 h-10 bg-gray-200">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="fill-current w-5 h-5">
                    <path d="M21.8 4H2.2c-.2 0-.3.2-.3.3v15.3c0 .3.1.4.3.4h19.6c.2 0 .3-.1.3-.3V4.3c0-.1-.1-.3-.3-.3zm-1.6 13.4l-4.4-4.6c0-.1-.1-.1-.2 0l-3.1 2.7-3.9-4.8h-.1s-.1 0-.1.1L3.8 17V6h16.4v11.4zm-4.9-6.8c.9 0 1.6-.7 1.6-1.6 0-.9-.7-1.6-1.6-1.6-.9 0-1.6.7-1.6 1.6.1.9.8 1.6 1.6 1.6z"/>
                </svg>
            </button>
        </div>
    </div>
</template>

<script>
    export default {
       name: 'NewPost',
       components: {

        }
    }
</script>

<style scoped>

</style>
