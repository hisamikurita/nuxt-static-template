<template>
  <footer ref="footer" class="footer">
    <div class="footer-bg">
      <div class="container">
        <div class="footer-logo">
          <svg-icon name="test" />
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer-bg{
  background-color: $black;
}

.footer-logo{
  width: vw(100);

  @include sp(){
    width: vw_sp(100);
  }

  & svg{
    width: 100%;
    height: 100%;
  }
}
</style>
