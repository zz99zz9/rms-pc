<template>
    <div class='index'>
        <div class='header'>
            <span class='hname'>{{hName}}</span><span class='uinfo'>当前操作人： {{uJobs}} {{uName}}</span>
        </div>
        

       <div class='right'>这是右侧的内容 固定宽度</div>

       <div class='left'><ul>
           <li class='li'><img src='../assets/img/book.svg'>订单</li>
           <li class='li'><img src='../assets/img/services.svg'>服务</li>
           <li class='li'><img src='../assets/img/status.svg'>房态</li>
           <li class='li'><img src='../assets/img/vip.svg'>会员</li>
           <li class='li'><img src='../assets/img/account.svg'>账户</li>
           <li class='li'><img src='../assets/img/setup.svg'>设置</li>
           </ul></div>

       <div class='main'>中间内容，自适应宽度</div>

  
    </div>
</template>

<script>
export default {
  name: 'index',
  data () {
      return{
    hName:'上海南汇店',
    uJobs:'前台',
    uName:'小朱'
    }
  }
}
</script>

<style>

</style>