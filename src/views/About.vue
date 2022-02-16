<template>
  <div class="about">
    <h1>Welcome to my Portofolio</h1>
    <img alt="wisnu" src="../assets/wisnu.jpg" style="width:158px;height:216px;">
    <p>
      Disini kamu akan menemukan keganjilan - keganjilan yang sangat ganjil <br>
      aneh bukan ya benar sangat aneh
    </p>
    <h2>Silahkan Masukan Pilihan Anda</h2>
    <ul>
      <li><a href="https://cdn-2.tstatic.net/batam/foto/bank/images/ilustrasi-harimau_20160413_175548.jpg" target="_blank" rel="noopener">Ini Macan</a></li>
      <li><a href="https://asset.kompas.com/crops/ncgvDkq11ovx_624dxbv483x_iY=/0x0:648x432/750x500/data/photo/2021/10/05/615c371c61b81.jpg" target="_blank" rel="noopener">Ini Panda</a></li>
      <li></li>
    </ul>
  </div>
</template>

<style scoped>
  h2 {
    margin-top: 100px;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  ul {
    list-style-type: none;
  }
  a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
export default {
  name: 'About',
};
</script>
