<template>
  <div>
    <!-- 標題介紹 -->
    <div class="py-20 flex flex-col justify-center borderBottom relative">
      <h2 class="text-[40px] font-bold">哈囉 ! 我是Sylvia👋</h2>
      <div class="my-6">
        <p class="text-2xl text-[#4C4136] mb-4">我是擁有13年設計領域經驗的設計師。</p>
        <p class="text-2xl text-[#4C4136]">我專注於<span class="bg-[#D7E9B8] rounded-lg p-3 mx-1">創造優質使用體驗</span>並<span
            class="bg-[#D7E9B8] rounded-lg p-3 mx-1">追求介面美感</span>，致力於將美學與功能性完美結合。</p>
      </div>
      <div class="font-bold mb-6 items-center flex">
        <Button @click="goAbout" :text="'關於我'" :bgColor="'#825514'" :textColor="'white'" :hoverBgColor="'#916930'" class="mr-4"></Button>
        <a @click="downloadpdf" class="btn bg-[#FFDDB9] w-[132px] border-none flex items-center hover:bg-[#E3C5A7]">
          <svg width="20" height="20" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M8 11.575C7.86667 11.575 7.74167 11.554 7.625 11.512C7.50833 11.4707 7.4 11.4 7.3 11.3L3.7 7.7C3.51667 7.51667 3.425 7.28333 3.425 7C3.425 6.71667 3.51667 6.48333 3.7 6.3C3.88333 6.11667 4.12067 6.02067 4.412 6.012C4.704 6.004 4.94167 6.09167 5.125 6.275L7 8.15V1C7 0.716667 7.096 0.479 7.288 0.287C7.47933 0.0956668 7.71667 0 8 0C8.28333 0 8.521 0.0956668 8.713 0.287C8.90433 0.479 9 0.716667 9 1V8.15L10.875 6.275C11.0583 6.09167 11.296 6.004 11.588 6.012C11.8793 6.02067 12.1167 6.11667 12.3 6.3C12.4833 6.48333 12.575 6.71667 12.575 7C12.575 7.28333 12.4833 7.51667 12.3 7.7L8.7 11.3C8.6 11.4 8.49167 11.4707 8.375 11.512C8.25833 11.554 8.13333 11.575 8 11.575ZM2 16C1.45 16 0.979333 15.8043 0.588 15.413C0.196 15.021 0 14.55 0 14V12C0 11.7167 0.0956668 11.479 0.287 11.287C0.479 11.0957 0.716667 11 1 11C1.28333 11 1.521 11.0957 1.713 11.287C1.90433 11.479 2 11.7167 2 12V14H14V12C14 11.7167 14.096 11.479 14.288 11.287C14.4793 11.0957 14.7167 11 15 11C15.2833 11 15.5207 11.0957 15.712 11.287C15.904 11.479 16 11.7167 16 12V14C16 14.55 15.8043 15.021 15.413 15.413C15.021 15.8043 14.55 16 14 16H2Z"
              fill="#2B1700" />
          </svg>
          下載履歷
        </a>
      </div>
      <p class="text-[#504539]">我熱愛學習與分享，並持續精進並回饋社群️‍️‍🌞️</p>
      <img class="w-[173px] h-[143px] absolute left-[-230px] top-[20px]" src="../assets/image/dot1.svg" alt="上點點">
      <img class="w-[173px] h-[143px] absolute right-[-160px] top-60" src="../assets/image/dot2.svg" alt="下點點">
    </div>
    <!-- 設計案例 -->
    <div class="py-20 flex flex-col items-center justify-center borderBottom">
      <p class="text-[32px] borderTitle mb-6">設計案例</p>
      <div class="my-6">
        <div>
          <div class="block rounded-lg designCase1">
            <img src="../assets/image/designCase1.svg" alt="設計案例1">
            <div class="w-[30%] p-4 aspect-square designCase1Content rounded-lg">
              <div class="h-full flex flex-col">
                <p class="text-[28px]">郵輪旅遊服務整合網站</p>
                <p class="text-base">一站式遊輪旅遊服務網站匯集郵輪資訊，讓消費者輕鬆比較和選擇行程與價格。提升市場透明度，促進業者競爭，支持旅遊產業復甦，並通過數據分析幫助業者優化產品，推動市場健康成長。
                </p>
                <div class="text-sm mt-4">
                  <div class="flex gap-1 w-full mb-4">
                    <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#UIUX 設計</span>
                    <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#使用者訪談</span>
                    <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#問卷調查</span>
                  </div>
                  <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#市場調查</span>
                </div>
                <a target="_blank" href="https://www.behance.net/gallery/204837457/SeaRate-"
                  class="btn bg-[#825514] text-white rounded-[100px] h-10 min-h-10 mt-auto w-full hover:bg-[#E3C5A7]">
                  了解專案
                  <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink">
                    <rect x="0.5" y="0.5" width="16" height="16" fill="url(#pattern0_76_81)" />
                    <defs>
                      <pattern id="pattern0_76_81" patternContentUnits="objectBoundingBox" width="1" height="1">
                        <use xlink:href="#image0_76_81" transform="scale(0.0104167)" />
                      </pattern>
                      <image id="image0_76_81" width="96" height="96"
                        xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgCAYAAADimHc4AAAACXBIWXMAAAsTAAALEwEAmpwYAAACH0lEQVR4nO2dMU7DUBAFXcBZgJqCo8EZCIHTRNwDOAcKhIoUgyxtEUGQI0T+W/99U+Of3RnHoUqGwRhjjDHGGGOMMcaYAwEugHvgBfigMcP0fKnm+TeAU+AB2LZecpcD5mxKS/mPJGAoGmC881MwVAsQz3zpY6d6gDR3f9UA4387aRgKBtiQiKFgAO0ADQAugVcHmJl8vwPE8h1ALN8BxPId4A8AV8D6QL+Tf9diYO0Aujt/HbEcQCU/rnMAlfy41gFU8uN6B1DJjzMcQCU/znEAlfw4ywFU8uM8B1DJjzMdQCU/znUAlfw42wFU8uN8B1DJj9dwAJX8eB0HUMlPgfwOqCw/WwCqyc8UgIryswSgqvwMAagsXx2A6vKVAbB8XQASyVfdgLIBSCS/XACSyS8VgITyywQgqfwSAUgsv/sAJJffdQBmIL/bAMxEfs8BbuYgv9sAI8B1dvldB5iIkEJ+9wF+iZBGfokA3yKkkl8mwM4Hcyr5pQJkRb6/fAAx8v3lA4iR7y8fQIx8f/kAYuT7ywcQI99fPoAY+f7yAcTI95cPIEa+v3wAMfL95QOIke8vH0CMfH/5AGLk+wPvU0MU5q3cVxcn46lFgKV6y8Tctghwnunr6xPxCZwdPUBE8LvgJ4sm8iPACbDaM0RVVqOTZgF2IiyLP462453fXP6ez4Q74DnbbwsciU3sumj2zDfGGGOMMcYYY4wxQw98AQuI/+97XYGIAAAAAElFTkSuQmCC" />
                    </defs>
                  </svg>
                </a>
              </div>
            </div>
          </div>
          <div class="block border border-[#D4C4B5] rounded-lg designCase1">
            <img src="../assets/image/designCase2.svg" alt="設計案例2">
            <div class="w-[30%] p-4 aspect-square shadow-xl bg-base-100 designCase1Content rounded-lg">
              <div class="h-full flex flex-col">
                <p class="text-[28px]">長照服務車輛媒合平台</p>
                <p class="text-base">
                  面對高齡化社會對移動服務的需求，我們推出了桃園地區的「長照服務車輛媒合平台」，透過共享經濟整合政府專車、復康巴士及民間租賃車輛資源，快速匹配長者及其家屬的交通需求。平台使用數位化系統，標準化服務管理，並計畫進一步整合長照2.0創新服務，實現「社會服務中的移動性」願景。
                </p>
                <div class="flex gap-1 text-sm mt-4">
                  <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#UIUX 設計</span>
                  <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#跨平台</span>
                  <span class="rounded-[100px] bg-[#FFDDB9] px-4 py-2">#設計系統</span>
                </div>
                <a target="_blank" href="https://www.behance.net/gallery/205943557/Matching-Platform" class="btn bg-[#825514] text-white rounded-[100px] h-10 min-h-10 mt-auto w-full hover:bg-[#E3C5A7]">
                  了解專案
                  <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink">
                    <rect x="0.5" y="0.5" width="16" height="16" fill="url(#pattern0_76_81)" />
                    <defs>
                      <pattern id="pattern0_76_81" patternContentUnits="objectBoundingBox" width="1" height="1">
                        <use xlink:href="#image0_76_81" transform="scale(0.0104167)" />
                      </pattern>
                      <image id="image0_76_81" width="96" height="96"
                        xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAABgCAYAAADimHc4AAAACXBIWXMAAAsTAAALEwEAmpwYAAACH0lEQVR4nO2dMU7DUBAFXcBZgJqCo8EZCIHTRNwDOAcKhIoUgyxtEUGQI0T+W/99U+Of3RnHoUqGwRhjjDHGGGOMMcaYAwEugHvgBfigMcP0fKnm+TeAU+AB2LZecpcD5mxKS/mPJGAoGmC881MwVAsQz3zpY6d6gDR3f9UA4387aRgKBtiQiKFgAO0ADQAugVcHmJl8vwPE8h1ALN8BxPId4A8AV8D6QL+Tf9diYO0Aujt/HbEcQCU/rnMAlfy41gFU8uN6B1DJjzMcQCU/znEAlfw4ywFU8uM8B1DJjzMdQCU/znUAlfw42wFU8uN8B1DJj9dwAJX8eB0HUMlPgfwOqCw/WwCqyc8UgIryswSgqvwMAagsXx2A6vKVAbB8XQASyVfdgLIBSCS/XACSyS8VgITyywQgqfwSAUgsv/sAJJffdQBmIL/bAMxEfs8BbuYgv9sAI8B1dvldB5iIkEJ+9wF+iZBGfokA3yKkkl8mwM4Hcyr5pQJkRb6/fAAx8v3lA4iR7y8fQIx8f/kAYuT7ywcQI99fPoAY+f7yAcTI95cPIEa+v3wAMfL95QOIke8vH0CMfH/5AGLk+wPvU0MU5q3cVxcn46lFgKV6y8Tctghwnunr6xPxCZwdPUBE8LvgJ4sm8iPACbDaM0RVVqOTZgF2IiyLP462453fXP6ez4Q74DnbbwsciU3sumj2zDfGGGOMMcYYY4wxQw98AQuI/+97XYGIAAAAAElFTkSuQmCC" />
                    </defs>
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <Button target="_blank" href="https://www.behance.net/siyu_chen/projects" :text="'查看更多專案'" :bgColor="'#825514'" :textColor="'white'" :hoverBgColor="'#916930'" class="px-8"></Button>
    </div>
    <!-- 互動  -->
    <div class="py-20 flex flex-col items-center justify-center borderBottom">
      <p class="text-[32px] borderTitle mb-6">互動/原型練習 </p>
      <div class="my-6">
        <div class="grid grid-cols-2">
          <img class="rounded-tl-lg"  src="../assets/image/screenityVideo.gif" alt="互動gif1">
          <img class="rounded-tr-lg" src="../assets/image/interactionGif2.gif" alt="互動gif2">
        </div>
        <div class="grid grid-cols-3">
          <img class="rounded-bl-lg" src="../assets/image/interactionGif3.gif" alt="互動gif3">
          <img src="../assets/image/interactionGif4.gif" alt="互動gif4">
          <img class="rounded-br-lg" src="../assets/image/interactionGif5.gif" alt="互動gif5">
        </div>
      </div>
      <Button target="_blank" href="https://dribbble.com/Sylvia0429" :text="'查看更多設計作品'" :bgColor="'#825514'" :textColor="'white'" :hoverBgColor="'#916930'" class="px-8"></Button>
    </div>
    <!-- 寫作文章 -->
    <div class="py-20 flex flex-col items-center justify-center borderBottom">
      <p class="text-[32px] borderTitle mb-6">寫作文章</p>
      <div class="grid grid-cols-3 gap-8 my-6">
        <a class="block" target="_blank" href="https://medium.com/@a0918109701/figma-animation-button-cfa5ebef4a5d">
          <div class="border border-[#D4C4B5] rounded-lg hover:shadow-md">
            <img class="rounded-lg" src="../assets/image/article1.svg" alt="寫作文章圖1">
          </div>
          <p class="text-xl font-bold mt-1">Figma五步驟輕鬆製作動畫按鈕</p>
        </a>
        <a class="block" target="_blank"
          href="https://medium.com/@a0918109701/%E4%BB%80%E9%BA%BC%E6%98%AF%E4%BD%BF%E7%94%A8%E8%80%85%E4%B8%AD%E5%BF%83%E8%A8%AD%E8%A8%88-%E5%A6%82%E4%BD%95%E8%AE%93%E4%BD%A0%E7%9A%84%E7%94%A2%E5%93%81%E7%9C%9F%E6%AD%A3%E7%82%BA%E4%BD%BF%E7%94%A8%E8%80%85%E6%9C%8D%E5%8B%99-1463ae0e9537">
          <div class="border border-[#D4C4B5]  rounded-lg hover:shadow-md">
            <img class="rounded-lg" src="../assets/image/article2.svg" alt="寫作文章圖2">
          </div>
          <p class="text-xl font-bold mt-1">什麼是使用者中心設計？如何讓你的產品真正為使用者服務？</p>
        </a>
        <a class="block" target="_blank"
          href="https://medium.com/@a0918109701/%E6%B7%B1%E5%85%A5%E4%BD%BF%E7%94%A8%E8%80%85%E9%9C%80%E6%B1%82-ux-%E7%A0%94%E7%A9%B6%E5%89%8D%E6%9C%9F%E7%9A%84%E4%B8%89%E5%A4%A7%E8%B3%AA%E6%80%A7%E6%96%B9%E6%B3%95-480a491cb1cd">
          <div class="border border-[#D4C4B5] rounded-lg hover:shadow-md">
            <img class="rounded-lg" src="../assets/image/article3.svg" alt="寫作文章圖3">
          </div>
          <p class="text-xl font-bold mt-1">深入使用者需求：UX 研究前期的三大質性方法</p>
        </a>
      </div>
      <Button target="_blank" href="https://medium.com/@a0918109701" :text="'查看更多文章'" :bgColor="'#825514'" :textColor="'white'" :hoverBgColor="'#916930'" class="px-8"></Button>
    </div>
    <!-- 商業設計 / 插畫 -->
    <div class="py-20 flex flex-col items-center justify-center borderBottom">
      <p class="text-[32px] borderTitle mb-6">商業設計 / 插畫</p>
      <div class="grid grid-cols-3 my-6 min-h-[630px] w-full">
        <div class="h-full">
          <div class="bg-[url('@/assets/image/illustration1.svg')] bg-cover bg-center h-1/2 w-full rounded-tl-lg"></div>
          <div class="bg-[url('@/assets/image/illustration2.svg')] bg-cover bg-center h-1/2 w-full rounded-bl-lg"></div>
        </div>
        <div>
          <div class="bg-[url('@/assets/image/illustration3.svg')] bg-cover bg-center h-2/3 w-full"></div>
          <div class="bg-[url('@/assets/image/illustration4.svg')] bg-cover bg-center h-1/3 w-full"></div>
        </div>
        <div>
          <div class="bg-[url('@/assets/image/illustration5.svg')] bg-cover bg-center h-full w-full rounded-r-lg"></div>
        </div>
      </div>
      <Button target="_blank" href="https://www.pinterest.com/joan062099/_created/" :text="'查看更多作品'" :bgColor="'#825514'" :textColor="'white'" :hoverBgColor="'#916930'" class="px-8"></Button>
    </div>
  </div>
</template>

<script setup>
import Button from '@/components/Button.vue'
import { useRouter } from 'vue-router'
const router = useRouter()

//往關於我
const goAbout = () => {
  router.push('/About')
}

const downloadpdf = () => {
  const pdfUrl = 'https://drive.usercontent.google.com/u/0/uc?id=1J7httZ4RvQPH692I-p1wqCJGYipG-jPV&export=download'; // PDF 文件的 URL
  const link = document.createElement('a'); // 創建一個隱藏的 <a> 標籤
  link.href = pdfUrl;
  link.setAttribute('download', 'Sylvia’s resume.pdf'); // 設置下載屬性，指定下載文件名
  document.body.appendChild(link);
  link.click(); // 模擬點擊以觸發下載
  document.body.removeChild(link); // 下載後移除標籤
}
</script>

<style>
.designCase1 {
  position: relative;
  /* 父容器設定為相對定位 */
  display: inline-block;
  /* 使容器的尺寸適應內容 */
  overflow: hidden;
  /* 隱藏超出容器的部分 */
}

.designCase1:hover::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: black;
  opacity: 0.4;
  /* 設置圖片在 hover 時的透明度 */
}

.designCase1Content {
  background-color: white;
  position: absolute;
  top: 50%;
  right: -500px;
  transform: translate(0%, -50%);
}

.designCase1:hover .designCase1Content {
  right: 25px;
  z-index: 10;
  transition: 0.1s 0.1s ease;
  /* 添加平滑的過渡效果 */
}
</style>
