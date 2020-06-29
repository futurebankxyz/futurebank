<template>
  <div>
    <nuxt />
  </div>
</template>
<style lang="scss">
@import '~bulma/sass/utilities/_all';

body {
  font-family: Tomorow;
  color: #fe65c4;
}

// FutureBank Colors
$primary: #fe65c4;
$primary-invert: findColorInvert($primary);
$dark: #333333;
$dark-invert: findColorInvert($dark);

// setup
$colors: (
  'dark': (
    $dark,
    $dark-invert
  ),
  'primary': (
    $primary,
    $primary-invert
  )
);

@import '~bulma';
@import '~buefy/src/scss/buefy';
</style>
