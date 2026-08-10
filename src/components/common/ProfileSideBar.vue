
<template>
    <div class="container">
        <div class="member-siedbar col-3">
            <h3>會員專區</h3>
            <div class="member-nav">
            <a href="">我的好友</a>
            <a href="">我的公會</a>
            <a href="">通知中心</a>
            <a href="">使用者設定</a>
            </div>
        </div>
    </div>
</template>

<script>
</script>


<style lang="scss" scoped>
@use "@/assets/scss/abstracts/variables" as *;

.member-siedbar{
    background-color:$neutral-200 ;
    
}

h3{
   font-size:$h5-size; 
   color:$primary;
}
.member-nav a{
  font-size: $label-md-size;
  color:$primary;
  display:flex;
  flex-direction: column;

}




</style>