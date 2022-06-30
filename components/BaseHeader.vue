<template>
  <header ref="header" class="header">
    <div class="header-bg">
      <div class="container">
        <div class="header-logo">
          <svg-icon name="test" />
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header-logo{
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
