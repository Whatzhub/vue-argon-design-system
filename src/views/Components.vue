<template>
    <div>
        <hero></hero>

        <section class="section section-lg">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-md-2">
            <img src="img/theme/promo-1.png" class="img-fluid floating" />
          </div>
          <div class="col-md-6 order-md-1">
            <div class="pr-md-5">
              <icon
                name="ni ni-settings-gear-65"
                class="mb-5"
                size="lg"
                type="success"
                shadow
                rounded
              ></icon>
              <h3>Awesome features</h3>
              <p>
                The kit comes with three pre-built pages to help you get started faster. You can change
                the text and images and you're good to go.
              </p>
              <ul class="list-unstyled mt-5">
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                    <h6 class="mb-0">Carefully crafted components</h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                    <h6 class="mb-0">Amazing page examples</h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                    <h6 class="mb-0">Super friendly support team</h6>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
        <!-- <basic-elements></basic-elements>
        <inputs></inputs>
        <custom-controls></custom-controls>
        <navigation></navigation>
        <javascript-components></javascript-components>
        <icons></icons>
        <examples></examples>
        <download-section></download-section>
        <carousel></carousel> -->
    </div>
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";

export default {
  name: "components",
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
