<template>
  <div class="container-fluid headermaindiv">
    <div class="nav-header">
      <div class="container header-container">
        <div class="row">
          <div class="col-md-12 pad-0">
            <nav class="navbar navbar-dark bg-dark navbar-expand-sm">
              <a class="navbar-brand" href="#">
                <div class="icon icon-bell-logo txtWhite hidden-xs hidden-sm txtSize34">
				</div>
               <!-- <span class="bellicon icon-bell-logo">
                  <img src="/src/images/bellIcon_76x76.png"/>
                </span>-->
                <span class="business-text bellSlim">Business<br />Portal</span>
              </a>
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbar-list-2"
                aria-controls="navbarNav"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbar-list-2">
                <ul class="navbar-nav">
                  <li class="nav-item item1">
                    <a class="nav-link" href="#">
                      <h1 class="header-title bellSlim">Register</h1>
                    </a>
                  </li>
                  <li class="nav-item item2">
                    <a class="nav-link" href="#">
                      <div class="lang-link">FR</div>
                    </a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "headpage",
  methods: {},
  data() {
    return {};
  },
  components: {},
};
</script>

<style>
</style>
