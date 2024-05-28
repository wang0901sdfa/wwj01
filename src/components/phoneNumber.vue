<template>
    <div>
        <h1>联系电话:1234567890</h1>
    </div>
    <div>
        <van-button round block type="danger" @click="confirm">返回上一页面</van-button>
    </div>
</template>

<script>
function confirm() {
    goBack();
  }
function goBack() {
    router.back();
  }
</script>

<style scoped>

</style>