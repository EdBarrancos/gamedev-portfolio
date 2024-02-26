<template>
  <div class="about-me">
    <div class="intro">
      Heyho, I'm
    </div>

    <div class="name">
      <h1>Eduardo Barrancos</h1>
    </div>

    <div class="paragraph">
      I am a Software Engineer
    </div>

    <div style="clear:both"></div>

    <div class="text-button">
      LEARN MORE
    </div>
    <div class="text-button">
      PORTOFOLIO
    </div>
    <div class="text-button">
      CONTACTS
    </div>

  </div>
</template>

<style scoped lang="less">

@import '../css/variables.less';

.about-me {
  margin-bottom: 293px;
  margin-top: 210px;
}

.intro {
  margin-bottom: 0.7em;
  text-align: left;
  padding-left: 15vw;
  color: @contentBgColor;
  stroke: yellow;
  stroke-width: .25em;
}

.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

h1 {
  text-align: center;
}

</style>