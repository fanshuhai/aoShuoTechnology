<template>
    <div class="headerStyle">
        <div class="headerInBox">
            <Row>
                <Col span="4">111</Col>
                <Col span="16">222</Col>
                <Col span="4">333</Col>
            </Row>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped lang="scss">
    .headerStyle{
      width: 100%;
      height: 70px;
      .headerInBox{
        width: 1200px;
        background-color:orangered;
        height: 70px;
        margin: 0 auto;
      }
    }
</style>
