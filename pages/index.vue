<template>
<div>
     <Navbar/>
     <!-- card -->
     <div class="container mx-auto">
       <div class="flex justify-between my-20">
         <h2 class="text-4xl font-bold">New Ads</h2>
         <ul class="flex">
           <li class="ml-8">
              <a href="#">For sale</a>
           </li>
           <li class="ml-8">
              <a href="#">Buying </a>
           </li>
           <li class="ml-8">
              <a href="#">For rent</a>
           </li>
           <li class="ml-8">
              <a href="#">Leasehold</a>
           </li>
        </ul>
       </div>
        <div class="flex justify-between flex-wrap">
          <Card v-for="(card,index) in 8" :key="index" />
        </div>
     </div>
     <section id="advantages">
       <div class="container mx-auto pt-32">
         <h2 class="text-4xl text-center font-bold mb-12">Our advantages</h2>
         <div>
           <ul class="flex justify-around flex-wrap">
             <li class="sliderBox">
               <div class="advantages__itemBG px-20 text-center">
                 <svg class="advantages__itemIcon" width="41" height="36" viewBox="0 0 41 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                 <path d="M5.2375 29.4286C5.2375 31.9533 7.41172 34 10.0937 34C12.7758 34 14.95 31.9533 14.95 29.4286C14.95 26.9038 12.7758 24.8571 10.0937 24.8571C7.41172 24.8571 5.2375 26.9038 5.2375 29.4286ZM5.2375 29.4286H2M35.7625 18C35.7625 15.4753 33.5883 13.4286 30.9062 13.4286C28.2242 13.4286 26.05 15.4753 26.05 18C26.05 20.5247 28.2242 22.5714 30.9062 22.5714C33.5883 22.5714 35.7625 20.5247 35.7625 18ZM35.7625 18H39M5.2375 6.57143C5.2375 9.09616 7.41172 11.1429 10.0937 11.1429C12.7758 11.1429 14.95 9.09616 14.95 6.57143C14.95 4.0467 12.7758 2 10.0937 2C7.41172 2 5.2375 4.0467 5.2375 6.57143ZM5.2375 6.57143H2M14.9449 6.57143H39M14.9449 29.4286H39M26.0551 18H2" stroke="#61A4DA" stroke-width="3.3" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <h3 class="text-xl font-bold my-6">Fine search settings and unique service capabilities</h3>
                <p class="text-base">There are more than 25 refinements to help you specify your needs.</p>
               </div>
               <img src="../static/person1.png" alt="" class="mx-auto">
             </li>
              <li class="sliderBox mt-24">
               <img src="../static/person2.png" alt="" class="mx-auto">

               <div class="advantages__itemBG px-20 text-center">
                 <svg class="advantages__itemIcon" width="41" height="36" viewBox="0 0 41 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                 <path d="M5.2375 29.4286C5.2375 31.9533 7.41172 34 10.0937 34C12.7758 34 14.95 31.9533 14.95 29.4286C14.95 26.9038 12.7758 24.8571 10.0937 24.8571C7.41172 24.8571 5.2375 26.9038 5.2375 29.4286ZM5.2375 29.4286H2M35.7625 18C35.7625 15.4753 33.5883 13.4286 30.9062 13.4286C28.2242 13.4286 26.05 15.4753 26.05 18C26.05 20.5247 28.2242 22.5714 30.9062 22.5714C33.5883 22.5714 35.7625 20.5247 35.7625 18ZM35.7625 18H39M5.2375 6.57143C5.2375 9.09616 7.41172 11.1429 10.0937 11.1429C12.7758 11.1429 14.95 9.09616 14.95 6.57143C14.95 4.0467 12.7758 2 10.0937 2C7.41172 2 5.2375 4.0467 5.2375 6.57143ZM5.2375 6.57143H2M14.9449 6.57143H39M14.9449 29.4286H39M26.0551 18H2" stroke="#61A4DA" stroke-width="3.3" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <h3 class="text-xl font-bold my-6">Fine search settings and unique service capabilities</h3>
                <p class="text-base">There are more than 25 refinements to help you specify your needs.</p>
               </div>
             </li>
              <li class="sliderBox">
               <div class="advantages__itemBG px-20 text-center">
                 <svg class="advantages__itemIcon" width="41" height="36" viewBox="0 0 41 36" fill="none" xmlns="http://www.w3.org/2000/svg">
                 <path d="M5.2375 29.4286C5.2375 31.9533 7.41172 34 10.0937 34C12.7758 34 14.95 31.9533 14.95 29.4286C14.95 26.9038 12.7758 24.8571 10.0937 24.8571C7.41172 24.8571 5.2375 26.9038 5.2375 29.4286ZM5.2375 29.4286H2M35.7625 18C35.7625 15.4753 33.5883 13.4286 30.9062 13.4286C28.2242 13.4286 26.05 15.4753 26.05 18C26.05 20.5247 28.2242 22.5714 30.9062 22.5714C33.5883 22.5714 35.7625 20.5247 35.7625 18ZM35.7625 18H39M5.2375 6.57143C5.2375 9.09616 7.41172 11.1429 10.0937 11.1429C12.7758 11.1429 14.95 9.09616 14.95 6.57143C14.95 4.0467 12.7758 2 10.0937 2C7.41172 2 5.2375 4.0467 5.2375 6.57143ZM5.2375 6.57143H2M14.9449 6.57143H39M14.9449 29.4286H39M26.0551 18H2" stroke="#61A4DA" stroke-width="3.3" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <h3 class="text-xl font-bold my-6">Fine search settings and unique service capabilities</h3>
                <p class="text-base">There are more than 25 refinements to help you specify your needs.</p>
               </div>
               <img src="../static/person3.png" alt="" class="mx-auto">
             </li>
           </ul>
         </div>
       </div>
     </section>
     <section id="popularSearches">
       <div class="container mx-auto">
         <h2 class="text-4xl font-bold mb-3 pt-4">Popular searches</h2>
         <div class="popularSearches__round">
           <div class="popularSearches__round_wrap">
            <div class="popularSearches__round_item">House by the river</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">Oddaja, Stanovanje,  Ljubljana okolica, cena do 500 EUR/mesec</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">2-room apartment</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">Prodaja, Stanovanje,  Ljubljana okolica, cena do 250.000 EUR</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">Oddaja, Stanovanje, Ljubljana mesto</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>

           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">5-room apartment</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">House by the river</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">3-room apartment</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">Prodaja, Stanovanje, 2,5-sobno, Ljubljana okolica, cena do 250.000 EUR</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">

           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">Oddaja, Stanovanje, Ljubljana mesto, cena do 500 EUR/mesec</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>
           <div class="popularSearches__round_wrap">
             <div class="popularSearches__round_item">1-room apartment</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>
           <div class="popularSearches__round_wrap">
            <div class="popularSearches__round_item">Nakup, Stanovanje,  Ljubljana mesto, cena do 250.000 EUR</div>
            <img src="../static/bg_hover.png" class="popularSearches__round_itemImg" alt="">
           </div>
         </div>
       </div>
     </section>
     <section id="ads">
       <div class="container mx-auto pt-4">
         <div class="flex justify-between items-center my-20">
         <h2 class="text-4xl font-bold">Popular Ads</h2>
         <ul class="flex">
           <li class="ml-8">
              <a href="#">For sale</a>
           </li>
           <li class="ml-8">
              <a href="#">Buying </a>
           </li>
           <li class="ml-8">
              <a href="#">For rent</a>
           </li>
           <li class="ml-8">
              <a href="#">Leasehold</a>
           </li>
        </ul>
       </div>
        <div class="flex justify-between flex-wrap">
          <Card v-for="(card,index) in 4" :key="index" />
        </div>
        </div>
     </section>
     <footer>
         <div class="container mx-auto">
            <div class="flex justify-between items-center font-bold pt-16">
              <ul class="footer__menu text-white flex">
                <li class="footer__item pr-10">About us</li>
                <li class="footer__item pr-10">Help and contacts</li>
                <li class="footer__item pr-10">FAQ</li>
                <li class="footer__item pr-10">Legal information</li>
              </ul>
              <div class="flex justify-around items-center">
                <select name="" id="" class="px-8 py-3 border rounded-full mr-4 bg-transparent text-white">
                  <option value="English">English</option>
                  <option value="English">English</option>
                </select>
                <select name="lang" id="lang" class="px-8 py-3 border rounded-full bg-transparent text-white">
                  <option value="USD">USD($)</option>
                  <option value="RUB">RUB</option>
                </select>
              </div>
          </div>
          <div class="mt-28 flex items-center justify-between">
            <div class="footer__copyRight text-white">
            © 2022 NEPREMICNINSKITRG — Svoje idealno mesto najdete tukaj
          </div>
          <div class="footer__social flex">
            <svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M12.9503 25.9999L12.962 26H12.958L12.9503 25.9999ZM13.042 26H13.038L13.0497 25.9999L13.042 26ZM12.9106 25.9997L12.9232 25.9998H12.916L12.9106 25.9997ZM13.084 25.9998H13.0768L13.0894 25.9997L13.084 25.9998ZM12.8723 25.9994L12.8807 25.9995L12.874 25.9994H12.8723ZM13.126 25.9994L13.1193 25.9995L13.1277 25.9994H13.126ZM13.1679 25.999L13.165 25.999L13.1763 25.9989L13.1679 25.999ZM12.8237 25.9989L12.835 25.999L12.8321 25.999L12.8237 25.9989ZM13.2098 25.9984L13.203 25.9985L13.2169 25.9983L13.2098 25.9984ZM12.7831 25.9983L12.797 25.9985L12.7902 25.9984L12.7831 25.9983ZM13.2517 25.9977L13.2424 25.9978L13.2553 25.9976L13.2517 25.9977ZM12.7447 25.9976L12.7576 25.9978L12.7483 25.9977L12.7447 25.9976ZM12.6971 25.9966L12.7085 25.9969L12.7065 25.9968L12.6971 25.9966ZM13.2935 25.9968L13.2915 25.9969L13.3029 25.9966L13.2935 25.9968ZM12.6553 25.9955L12.671 25.9959L12.6647 25.9958L12.6553 25.9955ZM13.3353 25.9958L13.329 25.9959L13.3447 25.9955L13.3353 25.9958ZM13.3771 25.9947L13.3669 25.995L13.3829 25.9945L13.3771 25.9947ZM12.6171 25.9945L12.6331 25.995L12.6229 25.9947L12.6171 25.9945ZM12.5805 25.9934L12.5919 25.9938L12.5812 25.9934L12.5713 25.9931L12.5805 25.9934ZM13.4188 25.9934L13.4081 25.9938L13.4195 25.9934L13.4287 25.9931L13.4188 25.9934ZM13.4605 25.992L13.4548 25.9922L13.4724 25.9916L13.4605 25.992ZM12.5276 25.9916L12.5452 25.9922L12.5395 25.992L12.5276 25.9916ZM12.4896 25.9902L12.508 25.9909L12.4978 25.9905L12.4896 25.9902ZM13.5022 25.9905L13.492 25.9909L13.5104 25.9902L13.5022 25.9905ZM12.4523 25.9887L12.4702 25.9894L12.4562 25.9889L12.4523 25.9887ZM13.5438 25.9889L13.5298 25.9894L13.5477 25.9887L13.5438 25.9889ZM12.4 25.9864L12.4193 25.9873L12.4145 25.9871L12.4 25.9864ZM13.5855 25.9871L13.5807 25.9873L13.6 25.9864L13.5855 25.9871ZM12.3624 25.9847L12.3824 25.9856L12.373 25.9852L12.3624 25.9847ZM13.627 25.9852L13.6176 25.9856L13.6376 25.9847L13.627 25.9852ZM12.3255 25.9828L12.3456 25.9838L12.3315 25.9831L12.3255 25.9828ZM13.6685 25.9831L13.6544 25.9838L13.6745 25.9828L13.6685 25.9831ZM13.7101 25.981L13.6917 25.9819L13.708 25.9811L13.7272 25.98L13.7101 25.981ZM12.292 25.9811L12.3083 25.9819L12.2899 25.981L12.2728 25.98L12.292 25.9811ZM13.7515 25.9786L13.7434 25.9791L13.764 25.9779L13.7515 25.9786ZM12.236 25.9779L12.2566 25.9791L12.2485 25.9786L12.236 25.9779ZM12.1993 25.9757L12.2199 25.9769L12.2071 25.9762L12.1993 25.9757ZM13.7929 25.9762L13.7801 25.9769L13.8007 25.9757L13.7929 25.9762ZM12.1643 25.9735L12.1829 25.9747L12.1656 25.9736L12.1482 25.9725L12.1643 25.9735ZM13.8344 25.9736L13.8171 25.9747L13.8357 25.9735L13.8518 25.9725L13.8344 25.9736ZM13.8757 25.971L13.8695 25.9714L13.8892 25.97L13.8757 25.971ZM12.1108 25.97L12.1305 25.9714L12.1243 25.971L12.1108 25.97ZM12.0742 25.9675L12.0935 25.9689L12.0829 25.9682L12.0742 25.9675ZM13.9171 25.9682L13.9065 25.9689L13.9258 25.9675L13.9171 25.9682ZM12.0377 25.9649L12.0554 25.9662L12.0417 25.9652L12.0377 25.9649ZM13.9583 25.9652L13.9446 25.9662L13.9623 25.9649L13.9583 25.9652ZM11.9886 25.9612L12.0041 25.9624L12.0004 25.9621L11.9886 25.9612ZM13.9996 25.9621L13.9959 25.9624L14.0114 25.9612L13.9996 25.9621ZM14.0408 25.9589L14.0334 25.9595L14.0492 25.9582L14.0408 25.9589ZM11.9508 25.9582L11.9666 25.9595L11.9592 25.9589L11.9508 25.9582ZM11.914 25.9552L11.9274 25.9563L11.918 25.9556L11.914 25.9552ZM14.082 25.9556L14.0726 25.9563L14.086 25.9552L14.082 25.9556ZM11.8735 25.9518L11.8775 25.9522L11.8768 25.9521L11.8735 25.9518ZM14.1232 25.9521L14.1225 25.9522L14.1265 25.9518L14.1232 25.9521ZM14.1643 25.9485L14.1607 25.9488L14.1698 25.948L14.1643 25.9485ZM11.8302 25.948L11.8393 25.9488L11.8357 25.9485L11.8302 25.948ZM11.7921 25.9445L11.7989 25.9452L11.7947 25.9448L11.7921 25.9445ZM14.2053 25.9448L14.2011 25.9452L14.2079 25.9445L14.2053 25.9448ZM10.9688 25.842C4.75724 24.8656 0 19.484 0 13C0 5.82513 5.82512 0 13 0C20.1749 0 26 5.82513 26 13C26 19.484 21.2428 24.8656 15.0312 25.842V16.7578H18.0604L18.6367 13H15.0312V10.5615C15.0312 9.53339 15.5349 8.53127 17.1498 8.53127H18.7891V5.33204C18.7891 5.33204 17.3014 5.07814 15.879 5.07814C12.9096 5.07814 10.9688 6.87783 10.9688 10.136V13H7.66797V16.7578H10.9688V25.842Z" fill="#61A4DA"/>
            </svg>
            <svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M13 0C20.1749 0 26 5.82512 26 13C26 20.1749 20.1749 26 13 26C5.82512 26 0 20.1749 0 13C0 5.82512 5.82512 0 13 0ZM13 4.875C10.7934 4.875 10.5167 4.88434 9.65006 4.9239C8.78526 4.96336 8.19462 5.10072 7.67777 5.30156C7.1435 5.50921 6.69038 5.78703 6.23868 6.23873C5.78698 6.69043 5.50916 7.14355 5.30151 7.67782C5.10067 8.19462 4.96336 8.78526 4.92385 9.65006C4.88434 10.5167 4.875 10.7934 4.875 13C4.875 15.2066 4.88434 15.4833 4.92385 16.3499C4.96336 17.2147 5.10067 17.8054 5.30151 18.3222C5.50916 18.8564 5.78698 19.3096 6.23868 19.7613C6.69038 20.213 7.1435 20.4908 7.67777 20.6985C8.19462 20.8993 8.78526 21.0366 9.65006 21.0761C10.5167 21.1157 10.7934 21.125 13 21.125C15.2066 21.125 15.4833 21.1157 16.3499 21.0761C17.2147 21.0366 17.8054 20.8993 18.3222 20.6985C18.8564 20.4908 19.3096 20.213 19.7613 19.7613C20.213 19.3096 20.4908 18.8564 20.6985 18.3222C20.8993 17.8054 21.0366 17.2147 21.0761 16.3499C21.1157 15.4833 21.125 15.2066 21.125 13C21.125 10.7934 21.1157 10.5167 21.0761 9.65006C21.0366 8.78526 20.8993 8.19462 20.6985 7.67782C20.4908 7.14355 20.213 6.69043 19.7613 6.23873C19.3096 5.78703 18.8564 5.50921 18.3222 5.30156C17.8054 5.10072 17.2147 4.96336 16.3499 4.9239C15.4833 4.88434 15.2066 4.875 13 4.875ZM13 6.33897C15.1695 6.33897 15.4264 6.34725 16.2832 6.38635C17.0754 6.42251 17.5056 6.55484 17.7919 6.66611C18.1712 6.81347 18.4418 6.98958 18.7261 7.27391C19.0105 7.55818 19.1865 7.82889 19.3339 8.20813C19.4452 8.49443 19.5775 8.9246 19.6136 9.71679C19.6528 10.5736 19.661 10.8305 19.661 13C19.661 15.1695 19.6528 15.4264 19.6136 16.2832C19.5775 17.0754 19.4452 17.5056 19.3339 17.7919C19.1865 18.1712 19.0105 18.4418 18.7261 18.7261C18.4418 19.0105 18.1712 19.1865 17.7919 19.3339C17.5056 19.4452 17.0754 19.5775 16.2832 19.6136C15.4266 19.6528 15.1696 19.661 13 19.661C10.8304 19.661 10.5735 19.6528 9.71679 19.6136C8.9246 19.5775 8.49443 19.4452 8.20813 19.3339C7.82884 19.1865 7.55818 19.0105 7.27386 18.7261C6.98953 18.4418 6.81347 18.1712 6.66611 17.7919C6.55484 17.5056 6.42246 17.0754 6.3863 16.2832C6.3472 15.4264 6.33897 15.1695 6.33897 13C6.33897 10.8305 6.3472 10.5736 6.3863 9.71679C6.42246 8.9246 6.55484 8.49443 6.66611 8.20813C6.81347 7.82889 6.98953 7.55818 7.27386 7.27391C7.55818 6.98958 7.82884 6.81347 8.20813 6.66611C8.49443 6.55484 8.9246 6.42251 9.71679 6.38635C10.5736 6.34725 10.8305 6.33897 13 6.33897ZM13 8.82771C10.6957 8.82771 8.82771 10.6957 8.82771 13C8.82771 15.3043 10.6957 17.1723 13 17.1723C15.3043 17.1723 17.1723 15.3043 17.1723 13C17.1723 10.6957 15.3043 8.82771 13 8.82771ZM13 15.7083C11.5042 15.7083 10.2917 14.4958 10.2917 13C10.2917 11.5042 11.5042 10.2917 13 10.2917C14.4958 10.2917 15.7083 11.5042 15.7083 13C15.7083 14.4958 14.4958 15.7083 13 15.7083ZM18.3122 8.66288C18.3122 9.20136 17.8756 9.63782 17.3371 9.63782C16.7987 9.63782 16.3622 9.20136 16.3622 8.66288C16.3622 8.12439 16.7987 7.68787 17.3371 7.68787C17.8756 7.68787 18.3122 8.12439 18.3122 8.66288Z" fill="#E9D986"/>
            </svg>

          </div>
          </div>
         </div>
     </footer>
</div>
</template>
<script>
import Card from '~/components/Card.vue';
export default {
    name: "IndexPage",
    components: { Card }
}
</script>

<style>
  body{
    overflow-x: hidden;
    font-family: 'Comfortaa', cursive;

  }
  .container{
    width: 1225px;
  }
  #advantages{
    height: 1034px;
    background: url('../static/advantagesBg.png') no-repeat top center / cover;
  }
  .advantages__itemBG{
    background: url('../static/sliderBlock1.png') no-repeat top left;
    height: 382px;
    width: 356px;
    padding-top: 54px;
  }
  .advantages__itemBG:nth-child(2){
        background: url('../static/sliderBlock2.png') no-repeat top left;
  }
  .sliderBox{
    width: 375px;
  }
  .advantages__itemIcon{
    position: relative;
    margin: 0 auto;
  }
  #popularSearches{
    height: 804px;
  }
  .popularSearches__round{
    position: relative;
  }
  
  .popularSearches__round_wrap{
    position: absolute;
    width: 98px;
    height: 98px;
    color:#61A4DA;
    text-align: center;
    border:2px solid #61A4DA;
    font-weight: bold;
    font-size: 11px;
    top:334px;
    border-radius: 360px;
    background: #fff;
    z-index: 10;
  }
  .popularSearches__round_itemImg{
    position: absolute;
    display: block;
    z-index: -8;
  }
  .popularSearches__round_wrap:nth-child(2){
    width: 212px;
    height: 212px;
    left:94px;
    top:173px;
    font-size: 14px;
  }
  .popularSearches__round_wrap:nth-child(3){
    top: 467px;
    width: 111px;
    height: 111px;
    left:60px;
  }
   .popularSearches__round_wrap:nth-child(4){
    top: 440px;
    width: 177px;
    height: 177px;
    left:200px;
    font-size: 14px;
  }
   .popularSearches__round_wrap:nth-child(5){
    top: 87px;
    width: 455px;
    height: 455px;
    left:349px;
    font-size: 14px;
  }
   .popularSearches__round_wrap:nth-child(6){
    top: 563px;
    width: 139px;
    height: 139px;
    left:427px;
    font-size: 14px;
  }
  .popularSearches__round_wrap:nth-child(7){
    top: 121px;
    width: 80px;
    height: 80px;
    left:773px;
    font-size: 12px;
  }
   .popularSearches__round_wrap:nth-child(8){
    top: 87px;
    width: 139px;
    height: 139px;
    left:872px;
    font-size: 14px;
  }
   .popularSearches__round_wrap:nth-child(9){
    top: 247px;
    width: 194px;
    height: 195px;
    left:837px;
    font-size: 14px;
  }
   .popularSearches__round_wrap:nth-child(10){
    top: 463px;
    width: 266px;
    height: 266px;
    left:708px;
    font-size: 14px;
  }
  .popularSearches__round_wrap:nth-child(11){
    top: 456px;
    width: 89px;
    height: 89px;
    left:994px;
    font-size: 10px;
  }
  .popularSearches__round_wrap:nth-child(12){
    top: 240px;
    width: 148px;
    height: 148px;
    left:1068px;
    font-size: 11px;
  }
  .popularSearches__round_wrap:hover{
    background: #E9D986;
    cursor: pointer;
    color:#000;
  }
  .popularSearches__round_wrap:hover .popularSearches__round_itemImg{
    display: block;
    z-index: -1;
  }
  .clearfix{
    content: '';
    clear:both;
    display: block;
  }
  #ads{
    height: 615px;
    background: url('../static/advantagesBg.png') no-repeat top center / cover;
}
  footer{
    background: url('../static/footerBG.png') no-repeat top center / cover;
    height: 269px;
  }
</style>
