<script setup>

</script>

<template>
  <footer class="text-center text-white footer" style="background-color: #f1f1f1;">
    <div class="container pt-4">
      <section class="mb-4 text-center">
        <!-- Tik Tok -->
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="https://www.tiktok.com/@koda.lib"
            role="button"
            data-mdb-ripple-color="dark"
            target="_blank"
        ><img src="../../assets/icons/tik-tok.svg" alt="tik-tok" class="icon-img"></a>

        <!-- VK -->
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="#!"
            role="button"
            data-mdb-ripple-color="dark"
            target="_blank"
        ><img src="../../assets/icons/vk.svg" alt="vk" class="icon-img"></a>

        <!-- Insta -->
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="https://www.instagram.com/koda.lib/"
            role="button"
            data-mdb-ripple-color="dark"
            target="_blank"
        ><img src="../../assets/icons/instagram.svg" alt="insta" class="icon-img"></a>

        <!-- Telega -->
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="https://t.me/kodalib"
            role="button"
            data-mdb-ripple-color="dark"
            target="_blank"
        ><img src="../../assets/icons/telegram.svg" alt="telega" class="icon-img"></a>

        <!-- Youtube -->
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="https://www.youtube.com/@kodalib"
            role="button"
            data-mdb-ripple-color="dark"
            target="_blank"
        ><img src="../../assets/icons/youtube.svg" alt="youtube" class="icon-img"></a>

      </section>
      <section class="mb-4 text-center">
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="/catalog"
            role="button"
            data-mdb-ripple-color=""
        >Каталог</a>
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="/genres"
            role="button"
            data-mdb-ripple-color="">
          Жанры
        </a>
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="/new"
            role="button"
            data-mdb-ripple-color="">
          Новое
        </a>
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="/top"
            role="button"
            data-mdb-ripple-color="">
          ТОП - 200
        </a>
        <a
            class="btn btn-link btn-floating btn-lg text-dark m-1"
            href="/films"
            role="button">
          Фильмы
        </a>

      </section>
    </div>

    <div class="text-center text-dark p-3" style="background-color: rgba(0, 0, 0, 0.2);">
      © 2023 Kodalib
    </div>
  </footer>
</template>

<style scoped>
.icon-img {
  width: 26px;
  height: 26px;
}

.footer{
  border-radius: 10px;
}
</style>