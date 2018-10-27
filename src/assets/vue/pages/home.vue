<template>
  <f7-page>
    <f7-navbar class="navbar color-theme-red">
      <f7-nav-left>
        <f7-link class="panel-open" open-panel="left" icon="fa fa-bars"></f7-link>
      </f7-nav-left>
      <div class="title">Speakintelligence</div>
      <f7-nav-right>
        <f7-link class="searchbar-enable" data-searchbar=".searchbar-components" icon="fa fa-search"></f7-link>
      </f7-nav-right>
      <f7-searchbar class="searchbar-components" search-container=".components-list" search-in="a" expandable></f7-searchbar>
    </f7-navbar>

    <f7-list class="searchbar-not-found">
      <f7-list-item title="Nothing found"></f7-list-item>
    </f7-list>
    <div class="hero-section">
      <h1 class="hero-title">Your Fully Automated Communications Webshop</h1>
      <p class="hero-subtitle">Simply add our customizable widget on your website and start increasing your revenue immediately</p>
      <div class="row">
        <div class="col-20"></div>
        <div class="col-60">
          <a class="button button-round button-fill button-raised color-red schedule-btn">Schedule Your Demo</a>
        </div>
        <div class="col-20"></div>
      </div>
      
    </div>
  </f7-page>
</template>
<script>
  export default {};

</script>


<style>
  .hero-section {
    height: 100vh;
    padding: 50px 0px;
    background: #F8D353;
    background: -webkit-linear-gradient(bottom right, #F8D353, #FF5C5A);
    background: -moz-linear-gradient(bottom right, #F8D353, #FF5C5A);
    background: linear-gradient(bottom right, #F8D353, #FF5C5A);
  }

  .hero-title {
    text-align: center;
    line-height: 1.2;
    font-size: 28px;
    margin-top: 6px;
    color: #fff;
  }

  .hero-subtitle {
    text-align: center;
    line-height: 1.2;
    font-size: 16px;
    padding: 10px;
    color: #fff;
  }

  .schedule-btn {
    margin-top: 20px;
  }

</style>
