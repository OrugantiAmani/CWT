<template>
  <div class="space40"></div>
  <div class="container header-container" style="padding: 0">
    <div class="row bgwhite compdiv margin-20-bottom">
      <div class="col-md-12 pad-0" style="display: flex">
        <div class="inlineBlock icon-width-40 text-center-xs">
          <i class="icon icon-info-outline-circled icon-size-medium txtBlue">
          </i>
        </div>
        <div
          class="inlineBlock pad-19-left no-pad-left-xs content-width valign-top"
        >
          <p class="txtBlack2 txtSize18 no-margin line-height-22">
            The Bell Business Portal gives you access to valuable, time-saving
            applications that help you manage your Bell Business services
            online. To register, select an application you require and enter the
            applicable information.
          </p>
        </div>
      </div>
    </div>
    <div class="flex">
      <div class="row">
        <div
          class="col-md-4 col bgwhite border-gray-light bgWhite pad-30"
          v-for="col in cols"
          :key="col"
        >
          <div class="innerdiv">
            <span class="txtBlack2 bellSlimSemibold txtSize24 line-height-26">
              {{ col.title }}
            </span>
            <div class="spacer15"></div>
            <p class="margin-20-bottom">{{ col.con }}</p>
            <br />
          </div>
          <button class="btn btn-default btn-block-xs">{{ col.btn }}</button>
        </div>
      </div>
    </div>
    <div class="spacer20"></div>
    <hr class="footer-line" />
  </div>
</template>
<script>
export default {
  name: "comppage",
  methods: {},
  data() {
    return {
      cols: [
        {
          title: "Online Bill Manager",
          con: "View, pay and manage your bills.",
          btn: "Register",
        },
        {
          title: "Online Business Account Manager",
          con:
            "View and make changes to your Business Internet account online.",
          btn: "Register",
        },
        {
          title: "DNS Management Tool",
          con: "Manage your custom domain settings online.",
          btn: "Register",
        },
      ],
    };
  },
  components: {},
};
</script>

<style>
</style>
