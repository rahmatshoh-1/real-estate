<template>
   <header>
        <nav class="flex justify-between items-center px-8">
        <ul class="flex justify-between w-60">
            <li class="flex">
               <img src="../static/slovenia_icon.png" alt="sloveniaFlag">
               <div class="ml-2">Slovenia</div>
            </li>
            <li class="flex">
                <img src="../static/italy_icon.png" alt="italyFlag">
               <div class="ml-2">Italy</div>
            </li>
            <li class="flex">
                <img src="../static/croatia_icon.png" alt="croatiaFlag">
               <div class="ml-2">Croatia</div>
            </li>
        </ul>
        <div class="flex justify-between py-3.5">
            <button type="button" class="p-2 px-5 bg-blue-500 text-white rounded-full flex items-center">
                <img src="../static/add.svg" alt="Add" class="mr-2">
                Add an ad
            </button>

            <div class="flex items-center mx-8">
                <div class="mr-2">
                    <img src="../static/list.svg" alt="listIcon">
                </div>
                <span>My Ads</span>
            </div>
             <div class="flex items-center">
                <div class="mr-2">
                    <img src="../static/favorite.svg" alt="favoriteIcon">
                </div>
                <span>Favorites</span>
            </div>
        </div>

        <div class="flex items-center">
               <div class="mr-2"> 
                   <img src="../static/chatIcon.svg" alt="chatIcon">
                </div>
                <span>Messages</span>
             <div class="flex ml-8">
                <img src="../static/LK.svg" alt="LkIcon">
            </div>
        </div>
        </nav>
        <div class="header">
            <img src="../static/logo.svg" alt="logo" class="logo mx-auto mt-12">
            <p class="text-center font-bold mt-4">Real estate in Pomurska</p>
            <div class="container mx-auto">
                <div class="booking__wrap mt-16">
                    <div class="booking__wrap__nav flex">
                        <a href="#">
                            <div class="booking_wrap_item booking_wrap_item_active ">
                            For sale
                            </div>
                        </a>
                        <a href="#">
                            <div class="booking_wrap_item">
                                Buying 
                            </div>
                        </a>
                        <a href="#">
                            <div class="booking_wrap_item">
                            For rent
                            </div>
                        </a>
                        <a href="#">
                            <div class="booking_wrap_item">
                            Leasehold
                            </div>
                        </a>
                    </div>
                    <div class="booking_wrap_content">
                        <form action="#" class="flex justify-between border rounded-full pl-4 py-2 bg-white">
                            <select name="" id="">
                                <option value="Apartment">Apartment</option>
                                <option value="Apartment">Apartment</option>
                                <option value="Apartment">Apartment</option>
                                <option value="Apartment">Apartment</option>
                                <option value="Apartment">Apartment</option>
                            </select>
                            <ul class="flex">
                                <li class="p-4 bg-gray-200 rounded-full">Studio</li>
                                <li class="px-6 py-4 bg-gray-200 rounded-full">1</li>
                                <li class="px-6 py-4 bg-gray-200 rounded-full">2</li>
                                <li class="px-6 py-4 border text-gray-200 rounded-full">3</li>
                                <li class="px-5 py-4 border text-gray-200 rounded-full">4+</li>
                            </ul>
                            <select name="" id="">
                                <option value="€20 — €20.000">€20 — €20.000</option>
                                <option value="€20 — €20.000">€20 — €20.000</option>
                                <option value="€20 — €20.000">€20 — €20.000</option>
                                <option value="€20 — €20.000">€20 — €20.000</option>
                                <option value="€20 — €20.000">€20 — €20.000</option>
                            </select>
                            <div class="flex items-center p-4">
                                <svg width="12" height="14" viewBox="0 0 12 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M10.2427 9.89947L6 14L1.75734 9.89947C0.918228 9.08846 0.346791 8.05518 0.115286 6.93029C-0.11622 5.8054 0.00260456 4.63942 0.456732 3.5798C0.91086 2.52017 1.67989 1.6145 2.66659 0.977301C3.65328 0.340103 4.81332 0 6 0C7.18668 0 8.34672 0.340103 9.33341 0.977301C10.3201 1.6145 11.0891 2.52017 11.5433 3.5798C11.9974 4.63942 12.1162 5.8054 11.8847 6.93029C11.6532 8.05518 11.0818 9.08846 10.2427 9.89947ZM6 8.37627C6.70724 8.37627 7.38552 8.10473 7.88562 7.62139C8.38571 7.13804 8.66667 6.48249 8.66667 5.79894C8.66667 5.11539 8.38571 4.45984 7.88562 3.97649C7.38552 3.49315 6.70724 3.22161 6 3.22161C5.29276 3.22161 4.61448 3.49315 4.11438 3.97649C3.61429 4.45984 3.33333 5.11539 3.33333 5.79894C3.33333 6.48249 3.61429 7.13804 4.11438 7.62139C4.61448 8.10473 5.29276 8.37627 6 8.37627ZM6 7.0876C5.64638 7.0876 5.30724 6.95183 5.05719 6.71016C4.80714 6.46849 4.66667 6.14071 4.66667 5.79894C4.66667 5.45716 4.80714 5.12939 5.05719 4.88772C5.30724 4.64604 5.64638 4.51027 6 4.51027C6.35362 4.51027 6.69276 4.64604 6.94281 4.88772C7.19286 5.12939 7.33333 5.45716 7.33333 5.79894C7.33333 6.14071 7.19286 6.46849 6.94281 6.71016C6.69276 6.95183 6.35362 7.0876 6 7.0876Z" fill="#61A4DA"/>
                                </svg>
                                <span class="city ml-2">Pomurska, Apače</span>
                            </div>
                            <button class="btn_search flex items-center mr-2">
                            <svg class="mr-2" width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M13.5121 11.9424L13.5197 11.95L13.5282 11.9564C13.7341 12.1108 13.85 12.3772 13.85 12.7273C13.85 13.3444 13.3444 13.85 12.7273 13.85C12.4501 13.85 12.1697 13.7394 11.9424 13.5121L8.88788 10.4576L8.8024 10.3721L8.7007 10.4375C7.83348 10.995 6.84336 11.3045 5.72727 11.3045C2.6283 11.3045 0.15 8.82625 0.15 5.72727C0.15 2.6283 2.6283 0.15 5.72727 0.15C8.82625 0.15 11.3045 2.6283 11.3045 5.72727C11.3045 6.84336 10.995 7.83348 10.4375 8.7007L10.3721 8.8024L10.4576 8.88788L13.5121 11.9424ZM5.72727 2.39545C3.86261 2.39545 2.39545 3.86261 2.39545 5.72727C2.39545 7.59193 3.86261 9.05909 5.72727 9.05909C7.59193 9.05909 9.05909 7.59193 9.05909 5.72727C9.05909 3.86261 7.59193 2.39545 5.72727 2.39545Z" fill="black" stroke="#E9D986" stroke-width="0.3"/>
                            </svg>
                            Search</button>
                        </form>
                    </div>
                    <div class="flex items-center ml-8 mt-5">
                        <svg width="15" height="13" viewBox="0 0 15 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M2.05 10.4286C2.05 11.2964 2.75515 12 3.625 12C4.49485 12 5.2 11.2964 5.2 10.4286C5.2 9.5607 4.49485 8.85714 3.625 8.85714C2.75515 8.85714 2.05 9.5607 2.05 10.4286ZM2.05 10.4286H1M12.95 6.5C12.95 5.63212 12.2448 4.92857 11.375 4.92857C10.5052 4.92857 9.8 5.63212 9.8 6.5C9.8 7.36788 10.5052 8.07143 11.375 8.07143C12.2448 8.07143 12.95 7.36788 12.95 6.5ZM12.95 6.5H14M2.05 2.57143C2.05 3.4393 2.75515 4.14286 3.625 4.14286C4.49485 4.14286 5.2 3.4393 5.2 2.57143C5.2 1.70355 4.49485 1 3.625 1C2.75515 1 2.05 1.70355 2.05 2.57143ZM2.05 2.57143H1M5.19835 2.57143H14M5.19835 10.4286H14M9.80165 6.5H1" stroke="#61A4DA" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <span class="mx-4">More parameters</span>
                        <svg width="7" height="6" viewBox="0 0 7 6" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M2.83103 4.75671L0.351861 2.00207C-0.169392 1.4229 0.241632 0.5 1.02083 0.5H5.97917C6.75837 0.5 7.16939 1.4229 6.64814 2.00207L4.16896 4.75671C3.81145 5.15395 3.18855 5.15395 2.83103 4.75671Z" fill="#61A4DA"/>
                        </svg>

                    </div>
                </div>
            </div>
            
        </div>
   </header>
</template>

<style scoped>
    header{
        background: url('../static/headerBg.png') no-repeat top center /cover;
        height: 512px;   
    }
    nav{
       font-family: 'Comfortaa', cursive;
       font-size: 12px;
       border-bottom: 1px solid #F1F1E7;
    }
    .logo{
        text-align: center;
    }
    .booking__wrap{
        position: relative;
    }
    .booking__wrap__nav {
        position: absolute;
        margin-top: -36px;
        z-index: 5;
    }
    .booking_wrap_content{
        position: relative;
        z-index: 10;
    }
    .booking_wrap_item{
        padding: 8px 16px 35px;
        margin-left: 10px;
        color: #61A4DA;
        cursor: pointer;
        border-top-left-radius: 15px;
        border-top-right-radius: 15px;
    }
    .booking_wrap_item:hover{
        color: #61A4DA;
        background: #F6F6EF;   
    }
    .booking_wrap_item_active{
        background: #61A4DA;
        color: #fff;
        border-top-left-radius: 15px;
        border-top-right-radius: 15px;
        padding: 8px 16px 35px;
        transition: all 0.3ms ease;
    }
    .btn_search{
        background: #E9D986;
        padding: 20px 40px;
        border-radius: 360px;
    }
</style>