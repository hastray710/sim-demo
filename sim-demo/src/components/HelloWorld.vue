<template>
  <div class="iot">
    <div calss="single-card">
      <ul>
    
      </ul>
    let a = 100
    </div>
        <!--左侧无序列表-->
    <div class="prompt">
        <text>共有卡{{sim_number1}}张 ,正使用{{sim_number2}}张 ,待激活{{sim_number3}}张 ,本月到期{{ sim_number4 }}张 , 账户余额{{account_balance}}元</text>

    </div>
    <!--右上方总状态实时显示-->


  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return {
      sim_number1:"19556",//总卡数
      sim_number2:"13372",//使用卡数
      sim_number3:"4502",//待激活卡数
      sim_number4:"562",//到期卡数
      account_balance:"562"//账户余额，记得浮点

    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
