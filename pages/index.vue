<template>
  <div class="flex fixed top-0 bottom-0 left-0 right-0">
    <img src="@/assets/png/coding-skeleton.png" alt="skeleton" />
    <div class="w-204 flex-end">
      <div class="w-92 mx-auto mt-40">
        <img src="@/assets/svg/logo.svg" alt="logo" />
        <div class="mb-8 mt-8">
          <h1 class="text-4xl mb-1">Login to Your Account</h1>
          <p>See what is going on with your business.</p>
        </div>
        <button class="rounded-lg border-2 border-gray-50 w-full h-11 mb-10">
          <div class="flex justify-center">
            <img src="@/assets/svg/google-icon.svg" class="mr-3"/>
            <p>Continue with Google</p>
          </div>
        </button>
        <div class="mb-10 w-full text-center">
          <a>----------or Sign in with Email----------</a>
        </div>
        <div class="mb-6">
          <label>Email</label>
          <input type="email" placeholder="mail@abc.com" class="pl-4 rounded-lg border-2 border-gray-50 w-full h-12"/>
        </div>
       <div class="mb-2">
          <label>Password</label>
          <input type="password" placeholder="************" class="pl-4 rounded-lg border-2 border-gray-50 w-full h-12"/>
       </div>
       <div class="flex justify-between mb-8">
        <input type="checkbox" name="Remember Me" />
         <p class="text-wine">forgot password?</p>
       </div>
       <button class="rounded-lg bg-wine border-2 border-gray-50 w-full h-12 mb-10">
          <div class="flex justify-center">
            <p class="text-white">Login</p>
          </div>
        </button>
        <p class="text-center">Not Registered Yet? <span class="text-wine">Create an account</span></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
