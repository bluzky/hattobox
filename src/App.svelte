<script>
  import logo from "./assets/logo.svg";
  import shopee from "./assets/shopee.png";
  import lazada from "./assets/lazada.png";
</script>

<main class="min-h-screen">
  <section class="text-gray-600 body-font">
    <div
      class="container mx-auto flex flex-col px-5 py-12 justify-center items-center"
    >
      <img
        class="lg:w-1/6 md:w-1/6 w-2/6 mb-10 object-cover object-center rounded"
        alt="hero"
        src={logo}
      />

      <div class="w-full md:w-2/3 flex flex-col mb-16 items-center text-center">
        <h1
          class="title-font sm:text-4xl text-3xl mb-4 font-black primary-text"
        >
          HATTO.BOX
        </h1>
        <content class="">
          <p class="text-lg text-yellow-900 font-bold mb-3">
            Chào mừng bạn đến với HATTO.BOX!
          </p>
          <p class="text-lg text-yellow-900 mb-3">
              Cũng đi làm văn phòng, <span class="primary-text font-bold"> Hatto</span> hiểu được đời sống nơi làm việc đã trở
            thành cuộc sống thứ 2 của chúng mình. Vậy thì mình phải chăm chút
            bàn làm việc để tạo ra một không gian thoải mái giúp bạn tập trung
            hơn, làm việc hiệu quả hơn và cũng như bảo vệ cơ thể tránh những ảnh
            hưởng xấu từ thói quen và tư thế làm việc chưa đúng.
          </p>
          <p class="text-lg text-yellow-900 mb-3">
            Ngoài ra một phần quan trọng không kém là những loại đồ uống và thực
            phẩm chúng ta dùng hàng ngày để có sức khỏe tốt hơn và bền bỉ hơn
            dưới áp lực công việc căng thẳng.
          </p>
          <p class="text-lg text-yellow-900 mb-5">
              Từ đó <span class="primary-text font-bold"> Hatto</span> mong muốn tạo ra nơi cung cấp mọi thứ bạn cần cho một
            nơi làm việc tuyệt vời nhất
          </p>
        </content>
        <p class="mt-2 text-xl primary-text mb-8 w-full">
          Website đang trong quá trình xây dựng. Ghé thăm HATTO trên đây nhé:
        </p>
        <div class="md:flex flex-col md:flex-row">
          <a
            href="https://shopee.vn/hattofoods.vn"
            class="bg-gray-100 inline-flex py-3 px-5 rounded-2xl items-center hover:border-emerald-600 border hover:bg-gray-200 focus:outline-none"
          >
            <img src={shopee} class="w-12 md:w-16" alt="Shopee logo" />
            <span class="ml-4 flex items-start flex-col leading-none">
              <span class="font-medium mb-1">HATTO.BOX</span>
              <span class="title-font">Trên Shopee</span>
            </span>
          </a>
          <a
            href="https://www.lazada.vn/shop/hatto-box/"
            class="bg-gray-100 inline-flex py-3 px-5 rounded-2xl ml-0 mt-5 md:ml-5 md:mt-0 items-center hover:border-emerald-600 border hover:bg-gray-200 focus:outline-none"
          >
            <img src={lazada} class="w-12 md:w-16" alt="Lazada logo" />
            <span class="ml-4 flex items-start flex-col leading-none">
              <span class="font-medium mb-1">HATTO.BOX</span>
              <span class="title-font">Trên Lazada</span>
            </span>
          </a>
        </div>
      </div>
    </div>
  </section>
</main>

<style>
  main {
    background-color: #fefeec;
  }

  .primary-text {
    color: #059145;
  }
</style>
