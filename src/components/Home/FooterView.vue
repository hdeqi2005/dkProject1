<template>
  <!--footer-->
  <footer class="footer hidden-xs no-padder text-center-nav-xs">
    <div class="bg hidden-xs ">
      <div class="dropdown dropup wrapper-sm clearfix">
        <a href="#" class="dropdown-toggle" data-toggle="dropdown"> <span class="thumb-sm avatar pull-left m-l-xs">
            <img src="../../../static/images/a3.png"  class="dker" alt="..." /> <i class="on b-black"></i> </span> <span class="hidden-nav-xs clear"> <span class="block m-l"> <strong class="font-bold text-lt">John.Smith</strong> <b class="caret"></b> </span> <span class="text-muted text-xs block m-l">Art Director</span> </span> </a>
        <ul class="dropdown-menu animated fadeInRight aside text-left">
          <li> <span class="arrow bottom hidden-nav-xs"></span> <a href="#">Settings</a> </li>
          <li> <a href="profile.html" >Profile</a> </li>
          <li> <a href="#"> <span class="badge bg-danger pull-right">3</span> Notifications </a> </li>
          <li> <a href="docs.html" >Help</a> </li>
          <li class="divider"></li>
          <li> <a href="modal.lockme.html"  data-toggle="ajaxModal">Logout</a> </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
    export default {
        name: "footerView"
    }
</script>

<style scoped>

</style>
