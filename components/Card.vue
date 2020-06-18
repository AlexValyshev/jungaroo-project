<template>
  <div class="card card_theme_light">
    <div class="card__container">
      <h2 class="card__heading card__heading_theme_light">Nulla volutpat aliquam velit</h2>
      <p class="card__text card__text_theme_light">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar ..</p>
      <div class="card__tag-container">
        <div class="card__oval card__oval_theme_light">
          <p class="card__user card__user_theme_light">OZ</p>
        </div>
        <p class="card__tag card__tag_theme_light">21.01.2020</p>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.card {
  max-width: 311px;
  width: 100%;
  padding: 16px 0;
  border: 1px solid blue;
  border-radius: 2px;
  display: flex;
}

.card_theme_light {
  background: #FFFFFF;
  box-shadow: 0px 3px 9px rgba(0, 0, 0, 0.227355);
}

.card__container {
  max-width: 279px;
  margin: 0 auto;
}

.card__heading {
  margin: 0;
  margin-bottom: 12px;
  font-family: "Open Sans", "Arial", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
}

.card__heading_theme_light {
  color: #646678;
}

.card__text {
  margin: 0;
  margin-bottom: 16px ;
  font-family: "Open Sans", "Arial", sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 24px;
}

.card__text_theme_light {
  color: rgba(100, 102, 120, 0.54);
}

.card__tag-container {
  display: flex;
}

.card__oval {
  width: 28px;
  height: 28px;
  border-radius: 50%;
  margin-right: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.card__oval_theme_light {
  background: #3591FB;
}

.card__user {
  margin: 0;
  font-family: "Lato", "Arial", sans-serif;
  font-style: normal;
  font-weight: 900;
  font-size: 10px;
  line-height: 12px;
}

.card__user_theme_light {
  color: #ffffff;
}

.card__tag {
  margin: 0;
  font-family: "Open Sans", "Arial", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 18px;
  text-align: right;
  align-self: center;
}

.card__tag_theme_light {
  color: #4DD86E;
}

</style>
