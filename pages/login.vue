<template>
    <div class="flex justify-center">
        <div class="mt-[100px] border p-6 rounded-[25px] w-[600px] bg">
            <div
                class="flex ml-[60px]  border items-center justify-between  text-[28px] shadow-lg w-[420px] h-[71px] rounded-[35px]"
            >
                <span @click="login=true" :class="{active: login}" class="py-3 px-20 rounded-[35px]">Login</span>
                
                <span @click="login=false" :class="{active: !login}" class="py-3 px-12 rounded-[35px]">Register</span>
            </div>
            <div class="flex justify-center mt-8">
                <img class="w-[70px] mr-6 h-[70px]" src="../public/images/Facebook.png" alt="">
                <img class="w-[70px] mr-6 h-[70px]"src="../public/images/Google.png" alt="">
                <img class="w-[70px] h-[70px]"src="../public/images/Twitter.png" alt="">
            </div>
            <div v-if="login" class="mt-[30px]">
                <input class="w-full px-4 border-b h-[72px]" type="text" placeholder="UserId">
                <input class="w-full px-4 border-b h-[72px]" type="text" placeholder="Enter Password">
                <div class="w-full flex items-center"><input class="h-[72px]" type="checkbox">
                <p class="ml-[10px]">Remember Me</p></div>
                
            </div>
            <div v-else class="mt-[30px]">
                <input class="w-full px-4 border-b h-[72px]" type="text" placeholder="UserId">
                <input class="w-full px-4 border-b h-[72px]" type="text" placeholder="Enter Password">
                <input class="w-full px-4 border-b h-[72px]" type="text" placeholder="Confirm Password">
                <div class="w-full flex items-center"><input class="h-[72px]" type="checkbox">
                <p class="ml-[10px]">Accept Terms and Conditions</p></div>


            </div>
            <div v-if="login" class="flex justify-center">
                <button class="bg-[#1A4722] text-[28px] text-white shadow-lg w-[220px] h-[60px] rounded-[35px]">Log In</button>
            </div>
            <div v-else class="flex justify-center">
                <button class="bg-[#1A4722] text-[28px] text-white shadow-lg w-[220px] h-[60px] rounded-[35px]">Register</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {

data() {
  return {
    login:true,

  }
},

methods: {

},

mounted() {
  console.log(`The initial count is ${this.count}.`)
}
}
</script>
<style scoped>
.active{
    background-color: #1A4722;
    color: white;
}
.bg{
    
    background-size: cover;
}


</style>
