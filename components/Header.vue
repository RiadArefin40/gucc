<template>
    <div>
        <div class="navbar  !bg-cyan-500 text-white">
            <div class="basis-1/3">
                
                <nuxt-link to="/" >
                    <img class="w-[50px]" src="https://i.ibb.co/RBfRd2m/305014596-441896544627879-514292066363765510-n.png" alt="" srcset="">
                </nuxt-link>
            </div>
            <div class="flex-1">
                <nuxt-link to="/photo" >
                    <a class="btn btn-ghost text-xl">Photo Gallery</a>
                </nuxt-link>
                <nuxt-link to="/notice" >
                    <a class="btn btn-ghost text-xl">Notice</a>
                </nuxt-link>
                <nuxt-link to="/committee" >
                    <a class="btn btn-ghost text-xl">Exe.Committee</a>
                </nuxt-link>
                <nuxt-link to="/photo" >
                    <a class="btn btn-ghost text-xl">Events</a>
                </nuxt-link>
                <nuxt-link to="/photo" >
                    <a class="btn btn-ghost text-xl">About</a>
                </nuxt-link>
                
         
             
         
            </div>
            <div class="flex-none gap-2">
                <div class="dropdown dropdown-end text-black">
                    <div
                        tabindex="0"
                        role="button"
                        class="btn btn-ghost btn-circle avatar"
                    >
                        <div class="w-10 rounded-full">
                            <img
                                alt="Tailwind CSS Navbar component"
                                src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg"
                            />
                        </div>
                    </div>
                    <ul
                        tabindex="0"
                        class="mt-3 z-[1] p-2 shadow menu menu-sm dropdown-content bg-base-100 rounded-box w-52"
                    >
                        <li>
                            <a class="justify-between">
                                Profile
                            </a>
                        </li>
                        <li><a>Logout</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>
