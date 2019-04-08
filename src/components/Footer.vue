<template>
  <div>
    <footer class="footer">
      <div class="copyright">
        <div>
          Copyright @ 2019- 2020

          <a href="http://nav.cwy.com">政府财务云产品中心</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
  export default {
    props: {
      beian: {
        type: String
      },
      gaBeian: {
        type: String
      },
      gaBeianHref: {
        type: String
      }
    },
    name: "nav-footer"
  }
</script>

<style>
  .footer {
    width: 100%;
    bottom: 0;
    line-height: 45px;
    background: #fff;
    box-shadow: 0 0 1rem rgba(0, 0, 0, 0.2);
  }

  .footer .copyright {
    margin-left: 30px;
    color: #949494;
    font-size: 12px;
  }

  .footer .copyright a {
    text-decoration: none;
    color: #3a85ff;
  }
</style>
