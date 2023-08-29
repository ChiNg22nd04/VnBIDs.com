<template>
  <div class="dark:bg-#232323">
    <div class="mx-auto container md:w-6xl lg:px-8 sm:px-8 px-5">
       <header class="pt-10 pb-12 xl:block hidden ">
       <div class="flex justify-between pb-6 border-b">
         <div class="flex">
           <a href="#" class="block i-ph:facebook-logo text-[18px] pr-8
           hover:text-blue-600 "></a>
           <a href="#" class="block i-ph:instagram-logo text-[18px] pr-8 hover:text-orange-800"></a>
           <a href="#" class="block i-ph:spotify-logo text-[18px] pr-8
           hover:text-green-400 "></a>
 
         </div>
         <div class="uppercase text-[10px] font-sans font-bold py-3 px-4 bg-[#f5f5f5] cursor-pointer dark:text-black"><a href="#" class="">subscribe</a></div>
       </div>
       <div class="py-4 flex border-b">
         <div class="flex-1 flex justify-center text-sm leading-200% uppercase">
           <a href="" class="  px-5 hover:text-gray-500">giới thiệu</a>
           <a href="" class="  px-5 hover:text-gray-500">sở thích</a>
           <a href="" class="  px-5 hover:text-gray-500">quan điểm-góc nhìn</a>
           <a href="" class="  px-5 hover:text-gray-500">công nghệ</a>
         </div>
         <div class="inline-block cursor-pointer px-5">
           <i class="inline-block hover:text-gray-500 i-ph:magnifying-glass"></i>
           <i class="inline-block hover:text-gray-500 i-ph:moon ml-2"></i>
         </div>
 
       </div>
       </header>
       <header class="xl:hidden flex justify-between items-center pt-10 pb-8 mb-10 border-b">
        <div class="px-5">
          <i class="block text-25px i-ph:list-bold"></i>
        </div>
        <div class="text-3xl hover:text-gray-500 font-extrabold cursor-pointer">
          <a href="#" class="">VnBIDs</a>
        </div>
        <div class="inline-block cursor-pointer px-5">
           <i class="inline-block text-25px hover:text-gray-500 i-ph:magnifying-glass"></i>
           <i class="inline-block text-25px hover:text-gray-500 i-ph:moon ml-2"></i>
         </div>
       </header>
       <nav class="">
          <ul class="uppercase bg-#f5f5f5 fixed top-0 left-0 bottom-0 z-20 translate-x-[-300px]">
            <p class="text-3xl px-10 py-6 text-center mt-10 mb-5 hover:text-gray-500 font-extrabold cursor-pointer border-b">
              <a href="#" class="">VnBIDs</a>
            </p>
            <li class="px-10 py-6 border-b">
              <a href="" class="  px-5 hover:text-gray-500">giới thiệu</a>
            </li>
            <li class="px-10 py-6 border-b">
              <a href="" class="  px-5 hover:text-gray-500">sở thích</a>
            </li>
            <li class="px-10 py-6 border-b">
              <a href="" class="  px-5 hover:text-gray-500">quan điểm-góc nhìn</a>
            </li>
            <li class="px-10 py-6 border-b">
              <a href="" class="  px-5 hover:text-gray-500">công nghệ</a>
              
            </li>
          </ul>
        </nav>
     <!-- <img src="https://toaitran.com/wp-content/uploads/2023/01/hannah-busing-Zyx1bK9mqmA-unsplash-scaled.jpg" class="h-140 w-full object-cover" /> -->
      <div class="bg-[url(https://toaitran.com/wp-content/uploads/2023/01/hannah-busing-Zyx1bK9mqmA-unsplash-scaled.jpg)] z-10 w-full h-290px md:h-140 bg-cover bg-center relative">
         <div class="absolute bottom-0 left-0 text-white p-8">
           <p class="uppercase text-4">nhật kí, công việc</p>
           <p class="text-12">Được - 2022</p>
           <ul class="uppercase flex text-15px sm:text-5 pb-5 justify-center items-center">
             <li class="">january 29, 2023</li>
             <div class="w-1 h-1 rounded-full bg-white mx-3"></div>
             <li class="">january 1, 2022</li>
           </ul>
           <div class="uppercase py-2 px-5 flex flex-col items-center text-black overflow-hidden text-3 bg-white w-114px">
             <!-- <p class="leading-7 w-114px m-1 py-2 px-5 overflow-hidden items-center mr-20">xem bài viết 
             </p> -->
             <div class="">
               <div class=" w-114px py-2 px-5 h-34px">xem bài viết</div>
               <!-- <div class="h-34px w-114px ">
                 <i class="text-10px py-2 px-5 flex block absolute i-carbon:arrow-right translate-y-[-20px] hover:transition-all  hover:duration-500 hover:translate-y-[0px]"></i>
               </div> -->
             </div>
             <!-- <p class=""><i class="block absolute left-20 i-carbon:arrow-right"></i>
             </p> -->
             <!-- <p class="hidden hover:block w-114px pb-15px"><i class=" hover:block absolute left-10 i-carbon:arrow-right"></i></p> -->
             <!-- hover:block translate-y-[-15px] hover:transition-all  hover:duration-500 hover:translate-y-[15px] -->
             <!-- <p class="inline-block translate-0 leading-7 py-2 px-5 hover:block hover:transition-all hover:duration-500 hover:translate-y-full ">xem bài viết</p> -->
           </div>
         </div>
         <div class="absolute right-0 bottom-0 flex p-32px">
           <a href="./index.vue" class="w-[8px] h-[8px] rounded-full bg-white mx-3"></a>
           <a href="./about.vue" class="w-[8px] h-[8px] rounded-full bg-white mx-3"></a>
         </div>
       </div>
       <div class="py-14 lg:flex lg:flex-cols-2  pt-12">
         <div class="flex flex-wrap flex-1">
           <div class="md:flex md:flex-cols-2 pb-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div> 
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b lg:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative flex-1">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10 hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-1 flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb xl:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>

           <div class="md:flex md:flex-cols-2 py-12 border-b w-95% ">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/02/pexels-joshua-welch-1624600-scaled.jpg)] w-full h-450px bg-cover bg-center mr-5 bg-no-repeat relative">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10   hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                     <div class="flex items-center text-[11px] mb-3 absolute bottom-0">
                       <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                       <div class="w-[2px] h-[2px] rounded-full bg-white mx-3"></div>
                       <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                       <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                       <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                    </div>
                 </a>
 
               </div>
             </div>
               
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b md:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10   hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb md:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b md:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10   hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb md:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b md:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10   hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb md:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="md:flex md:flex-cols-2 py-12 border-b md:w-92% md:mr-3">
             <div href="" class="block bg-[url(https://toaitran.com/wp-content/uploads/2022/10/caleb-fisher-7wdokBOQKGY-unsplash-560x420.jpg)] w-full h-60 bg-cover bg-center mr-5 bg-no-repeat relative">
               <div class="w-full h-full hover:bg-gray-900 hover:bg-opacity-10   hover:transition-all hover:ease-in-out hover:duration-150 relative group">
                 <a class="hidden group-hover:flex flex-col w-full h-full">
                   <p class="flex justify-center items-center  uppercase text-white text-10px w-full h-full">xem bài viết<i class="block i-carbon:arrow-right ml-2"></i>
                   </p>
                   <p class="border-b w-80% mx-auto"></p>
                   <p class="uppercase text-10px text-center text-white my-4">4 minute read</p>
                 </a>
 
               </div>
             </div>
               <div class="flex justify-between flex-col md:mx-5 md:pt-0 pt-5">
                 <div class="">
                   <a href="#" class="block uppercase text-[11px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                     quan điểm góc nhìn
                   </a>
                   <a href="" class="block text-2xl my-3 hover:text-gray-500">Tuột mood thì làm gì?
                   </a>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">February 16, 2020</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">no comment</a>
                   </div>
                   <p class="text-[14px] leading-6 text-[#333] dark:text-#dbdbdb md:pr-20">Thực sự để viết thành một bài viết hoàn chỉnh về 1 chủ đề nào đó, mình sẽ cần dành rất nhiều thời gian để nghiên cứu, cung cấp thông tin chính xác, khách quan. Đó là lí do mình ít viết về…
                   </p>
                 </div>
                 <div class="flex mt-5 md:mt-0">
                   <div class="text-[#c9c9c9] text-10px flex items-center mr-2">
                     <p class="uppercase">share</p>
                     <i class="block i-carbon:arrow-right ml-2"></i>
                   </div>
                   <div class="flex text-#333 dark:text-#dbdbdb">
                     <a href="" class="">
                       <i class="block i-ph:facebook-logo mx-1 hover:text-blue-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:twitter-logo mx-1 hover:text-sky-400"></i>
                     </a>
                     <a href="" class="">
                       <i class="block i-ph:pinterest-logo-fill mx-1  hover:text-red-500"></i>
                     </a>
                   </div>
                 </div>
               </div>
           </div>
           <div class="flex flex-1 justify-center pt-10">
             <div class="uppercase text-[10px] font-sans font-bold py-3 px-5 bg-[#f5f5f5] cursor-pointer dark:text-black"><a href="#" class="">learn more</a></div>
           </div>
         </div>
         <div class="md:w-30% relative md:pt-0 pt-5 xl:px-3">
           <div class="sticky mt-auto bottom-60px top-0">
               <a href="#" class="block uppercase text-3 mb-3">INSTAGRAM</a>
               <a href="#" class="block uppercase text-3 mb-5">TRENDING POSTS</a>
               <div class="flex flex-cols-2">
                 <div class="bg-[url(https://toaitran.com/wp-content/uploads/2023/02/rene-bohmer-YeUVDKZWSZ4-unsplash-scaled-e1675275718719.jpg)] bg-center bg-cover xl:w-30 w-52 h-25 mr-4">
                   <div class="hover:bg-gray-900 hover:bg-opacity-10 w-full h-full"></div>
                 </div>
                 <div class="flex flex-col justify-between">
                   <div class="flex flex-col">
                     <a href="#" class="block uppercase text-[10px] text-[#333] dark:text-#dbdbdb hover:text-gray-500">
                       công nghệ
                     </a>
                     <a href="" class="block text-18px my-3 leading-6 hover:text-gray-500">3 giải thích dễ hiểu về ChatGPT
                     </a>
                   </div>
                   <div class="flex items-center text-[11px] mb-3">
                     <a href="#" class="font-bold hover:text-gray-500">VnBIDs</a>
                     <div class="w-[2px] h-[2px] rounded-full bg-black mx-3"></div>
                     <a href="#" class="uppercase hover:text-gray-500">january 1, 2022</a>
                   </div>
                 </div>
               </div>
           </div>
         </div>
       </div>
     </div>
  </div>
    <div class="pb-100 pt-20 bg-#fbfbfb dark:bg-black">
      <div class="container m-auto  lg:w-6xl lg:px-8 xl:px-0 px-3">
        <div class="text-center">
          <p class="">© 2023 VnBIDs. Tất cả các quyền được bảo lưu.</p>
        </div>
        <div class="">
          <div class="text-center">
            <p class="font-extrabold text-2xl my-4">VnBIDs Media</p>
            <div class="flex justify-center sm:items-center items-start mb-3">
              <i class="block i-ph:map-pin-light text-25px sm:text-13px sm:mr-2"></i>
              <p class="">Tầng 8, Pearl Plaza, 561A Đ. Điện Biên Phủ, Phường 25, Bình Thạnh, Thành phố Hồ Chí Minh</p>
            </div>
          </div>
          <div class="flex justify-center">
            <div class="flex items-center md:justify-center justify-start flex-1">
              <i class="block i-ph:envelope-fill sm:mr-2 mr-2px"></i>
              <p class="">contact@VnBIDs.com.vn</p>
            </div>
            <!-- <div class="mx-16"></div> -->
            <div class="flex items-center md:justify-center justify-end flex-1">
              <i class="block i-ph:phone-duotone sm:mr-2 mr-2px "></i>
              <p class="">(028) 3865 0991</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    






      <!-- <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8 my-20">
        <Card  v-for="(item) in data" :title="item.title" :content="item.content"/>
      </div> -->


</template>
  
<script setup lang='ts'>

// const data = [
//   {
//     title: 'Card 1',
//   content: 'm ducimus accusantium nemo earum possimus eligendi, et enim facilis. Explicabo molestiae mollitia assumenda voluptates dolor tempora doloribus reprehenderit, ipsum maiores omnis?'
//   },
//   {
//     title: 'Card 2',
//   content: 'm ducimus accusantium nemo earum possimus eligendi, et enim facilis. Explicabo molestiae mollitia assumenda voluptates dolor tempora doloribus reprehenderit, ipsum maiores omnis?'
//   },
//   {
//     title: 'Card 3',
//   content: 'm ducimus accusantium nemo earum possimus eligendi, et enim facilis. Explicabo molestiae mollitia assumenda voluptates dolor tempora doloribus reprehenderit, ipsum maiores omnis?'
//   },

// ]


  
</script>
