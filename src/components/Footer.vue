<template>
    <div>
        <footer class="footer">
    <p>Questions? Call 1-200-768-71123</p>
    <div class="footer-cols">
      <ul>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Bank Safety</a></li>
        <li><a href="#">Bank Notifications</a></li>
        <li><a href="#">Corporate Information</a></li>
        <li><a href="#">What is BAAAKX ?</a></li>
      </ul>
      <ul>
        <li><a href="#">How can we improve ?</a></li>
        <li><a href="#">Location</a></li>
        <li><a href="#">Legal Notices</a></li>
      </ul>
       <ul>
        <li><a href="#">FAQ</a></li>
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Speed Test</a></li>
      </ul>
      <ul>
        <li><a href="#">Help Center</a></li>
        <li><a href="#">Terms Of Use</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </div>
    <a href="#" target="_blank">
        <i class="fab fa-linkedin"></i>
      </a>
      <a href="#" target="_blank">
        <i class="fab fa-instagram"></i>
      </a>
      <a href="#" target="_blank">
          <i class="fab fa-twitter"></i>
      </a>
</footer>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>
    ul{
    list-style: none;
}
.footer,
.footer a {
    color: #999;
    font-size: 0.9rem;
    background-color: black;
    font-size: 15px;
    padding: 10px;
    text-decoration: none;
}
.fab{
    font-size: 30px;
}
footer a:hover{
    color: #F3DC5C ;
}
.footer p {
    margin-bottom: 1.5rem;
}
.footer .footer-cols {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 2rem;
}
.footer li {
    line-height: 1.9;
}
</style>