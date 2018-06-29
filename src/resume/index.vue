<template>
  <div id="sxy">
    <div class="head__wrapper">
      <div class="sxy__photo"></div>
      <div class="sxy__name">申鑫宇</div>
    </div>
    <div class="body__wrapper">
      <div class="sxy__info">
        <div></div>
        <div></div>
      </div>
    </div>
    <div class="footer_wrapper"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      info: {
        edu: '浙江理工大学信息与计算机科学',
        tel: '17826859626',
        email: '1569860141@qq.com'
      }
    }
  }
}
</script>

<style lang="scss" scoped>
#sxy {
  display: flex;
  flex-direction: column;
  margin: 100px auto;
  height: 800px;
  width: 600px;
}

.head__wrapper {
  display: flex;
  align-items: center;
  background-color: #dcdcdc;
  height: 150px;
}

.sxy__photo {
  height: 120px;
  width: 100px;
  margin-left: 50px;
  background-color: azure;
}

.sxy__name {
  font-size: 30px;
  margin-left: 80px;
}
</style>
