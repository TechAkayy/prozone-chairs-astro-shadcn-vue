<script setup lang="ts">
	// const props = defineProps({
	// 	name: {
	// 		type: String,
	// 		default: 'FooterSection',
	// 	},
	// })

	// const emit = defineEmits(['addToCart'])

	// // Use the addToCart function like this:
	// // Eg-1: addToCart('pizza', 10)
	// // Eg-2: (event) => addToCart('pizza', 10, event)
	// const addToCart = (item, quantity /*, event*/) => {
	// 	emit('addToCart', { item, quantity })
	// }
</script>
<template>
    <footer class="bg-black bg-opacity-90 font-light pt-12 text-center text-white">
        <div class="container mx-auto px-4 py-6 relative"><a href="#" class="flex-col font-bold hover:text-opacity-75 inline-flex items-center leading-none mb-6 text-3xl text-center text-secondary-500 uppercase"> <svg version="1.0" xmlns="http://www.w3.org/2000/svg" width="2.4em" xml:space="preserve" fill="currentColor" viewBox="0 0 100 100" height="2.4em">
                    <path d="M63.334 10H36.666C33.002 10 30 13.001 30 16.667v46.666h40V16.667C70 13.001 66.998 10 63.334 10z"/>
                    <path d="M76.666 36.667c-.568 0-1.113.098-1.666.169v31.497H25V36.836c-.553-.071-1.094-.169-1.666-.169C15.971 36.667 10 42.637 10 50c0 4.929 2.699 9.18 6.666 11.484V70h.004-.004c0 7.363 5.971 13.333 13.334 13.333V90h6.666v-6.667h26.668V90H70v-6.667c7.363 0 13.33-5.97 13.334-13.333v-8.516C87.301 59.18 90 54.929 90 50c0-7.363-5.971-13.333-13.334-13.333z"/>
                </svg> <span>Prozone<br/>Chair</span> </a>
            <div class="flex flex-wrap justify-center mb-6"><a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">Home</a>
                <a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">About</a>
                <a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">Products</a>
                <a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">Shop</a>
                <a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">Blog</a>
                <a href="#" class="font-light hover:text-opacity-75 px-4 py-2 text-white">Contact</a>
            </div>
            <div class="flex-wrap inline-flex mb-6 space-x-4"><a href="#" aria-label="facebook" class="hover:text-opacity-50 text-white"> <svg viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5">
                        <path d="M14 13.5h2.5l1-4H14v-2c0-1.03 0-2 2-2h1.5V2.14c-.326-.043-1.557-.14-2.857-.14C11.928 2 10 3.657 10 6.7v2.8H7v4h3V22h4v-8.5z"/>
                    </svg></a><a href="#" aria-label="twitter" class="hover:text-opacity-50 text-white"> <svg viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5">
                        <path d="M22.162 5.656a8.384 8.384 0 0 1-2.402.658A4.196 4.196 0 0 0 21.6 4c-.82.488-1.719.83-2.656 1.015a4.182 4.182 0 0 0-7.126 3.814 11.874 11.874 0 0 1-8.62-4.37 4.168 4.168 0 0 0-.566 2.103c0 1.45.738 2.731 1.86 3.481a4.168 4.168 0 0 1-1.894-.523v.052a4.185 4.185 0 0 0 3.355 4.101 4.21 4.21 0 0 1-1.89.072A4.185 4.185 0 0 0 7.97 16.65a8.394 8.394 0 0 1-6.191 1.732 11.83 11.83 0 0 0 6.41 1.88c7.693 0 11.9-6.373 11.9-11.9 0-.18-.005-.362-.013-.54a8.496 8.496 0 0 0 2.087-2.165z"/>
                    </svg></a><a href="#" aria-label="instagram" class="hover:text-opacity-50 text-white"> <svg viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5">
                        <path d="M12 2c2.717 0 3.056.01 4.122.06 1.065.05 1.79.217 2.428.465.66.254 1.216.598 1.772 1.153a4.908 4.908 0 0 1 1.153 1.772c.247.637.415 1.363.465 2.428.047 1.066.06 1.405.06 4.122 0 2.717-.01 3.056-.06 4.122-.05 1.065-.218 1.79-.465 2.428a4.883 4.883 0 0 1-1.153 1.772 4.915 4.915 0 0 1-1.772 1.153c-.637.247-1.363.415-2.428.465-1.066.047-1.405.06-4.122.06-2.717 0-3.056-.01-4.122-.06-1.065-.05-1.79-.218-2.428-.465a4.89 4.89 0 0 1-1.772-1.153 4.904 4.904 0 0 1-1.153-1.772c-.248-.637-.415-1.363-.465-2.428C2.013 15.056 2 14.717 2 12c0-2.717.01-3.056.06-4.122.05-1.066.217-1.79.465-2.428a4.88 4.88 0 0 1 1.153-1.772A4.897 4.897 0 0 1 5.45 2.525c.638-.248 1.362-.415 2.428-.465C8.944 2.013 9.283 2 12 2zm0 5a5 5 0 1 0 0 10 5 5 0 0 0 0-10zm6.5-.25a1.25 1.25 0 0 0-2.5 0 1.25 1.25 0 0 0 2.5 0zM12 9a3 3 0 1 1 0 6 3 3 0 0 1 0-6z"/>
                    </svg></a>
                <a href="#" aria-label="linkedin" class="hover:text-opacity-50 text-white"> <svg viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5">
                        <path d="M6.94 5a2 2 0 1 1-4-.002 2 2 0 0 1 4 .002zM7 8.48H3V21h4V8.48zm6.32 0H9.34V21h3.94v-6.57c0-3.66 4.77-4 4.77 0V21H22v-7.93c0-6.17-7.06-5.94-8.72-2.91l.04-1.68z"/>
                    </svg></a>
                <a href="#" aria-label="youtube" class="hover:text-opacity-50 text-white"> <svg viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5">
                        <path d="M21.543 6.498C22 8.28 22 12 22 12s0 3.72-.457 5.502c-.254.985-.997 1.76-1.938 2.022C17.896 20 12 20 12 20s-5.893 0-7.605-.476c-.945-.266-1.687-1.04-1.938-2.022C2 15.72 2 12 2 12s0-3.72.457-5.502c.254-.985.997-1.76 1.938-2.022C6.107 4 12 4 12 4s5.896 0 7.605.476c.945.266 1.687 1.04 1.938 2.022zM10 15.5l6-3.5-6-3.5v7z"/>
                    </svg></a>
            </div>
            <AllOpeningHours></AllOpeningHours>
        </div>
        <hr class="opacity-25 md:mt-4"/>
        <div class="container mx-auto px-4 relative md:text-left">
            <div class="py-4 text-sm">
                <div class="flex flex-wrap -mx-4 items-center" data-pg-class-style="column_parent" data-pg-class-style-inline=" items-center">
                    <div class="px-4 py-2 w-full md:flex-1">
                        <p>&copy; 2002 - 2021. All Rights Reserved - Company Name</p>
                    </div>
                    <div class="px-4 py-2 w-full md:w-auto"><a href="#" class="hover:text-opacity-50 hover:underline text-white">Privacy Policy</a>
                        |<a href="#" class="hover:text-opacity-50 hover:underline text-white">Terms of Use</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style scoped></style>
