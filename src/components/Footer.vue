<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-box">
        <router-link to="/" class="footer-logo">
          <img src="../assets/images/logo.svg" alt="logo">
        </router-link>
        <div class="footer-nav">
          <ul>
            <li>
              <a href="goods.html">Ресторанам</a>
            </li>
            <li>
              <a href="goods.html">Курьерам</a>
            </li>
            <li>
              <a href="goods.html">Пресс-центр</a>
            </li>
            <li>
              <a href="goods.html">Контакты</a>
            </li>
          </ul>
        </div>
        <div class="footer-social">
          <img src="../assets/images/social/Inst.png" alt="Inst">
          <img src="../assets/images/social/fb.png" alt="FB">
          <img src="../assets/images/social/vk.png" alt="VK">
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  min-height: 156px;
  padding: 60px 0;
}

.footer-box {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 36px;
  height: 100%;

}

.footer-nav {
  flex-grow: 1;
}

.footer-nav ul {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  margin: 0;
  padding: 0;
  list-style: none;
  gap: 15px;
}

.footer-nav ul li {
  font-weight: 400;
  font-size: 18px;
  color: #595959;
}

.footer-nav ul li a {
  text-decoration: none;
  color: #595959;
}

.footer-social {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: 20px;
}
</style>