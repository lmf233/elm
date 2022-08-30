<template>
  <div class="wrapper">
    <!-- header部分 -->
    <header>
      <p>我的订单</p>
    </header>
    <!-- 订单列表部分 -->
    <h3>未支付订单信息：</h3>
    <ul class="order">
      <li>
        <div class="order-info">
          <p>
            万家饺子（软件园E18店）
            <i class="fa fa-caret-down"></i>
          </p>
          <div class="order-info-right">
            <p>&#165;49</p>
            <div class="order-info-right-icon">去支付</div>
          </div>
        </div>
        <ul class="order-detailet">
          <li>
            <p>纯肉鲜肉（水饺） x 2</p>
            <p>&#165;15</p>
          </li>
          <li>
            <p>玉米鲜肉（水饺） x 1</p>
            <p>&#165;16</p>
          </li>
          <li>
            <p>配送费</p>
            <p>&#165;3</p>
          </li>
        </ul>
      </li>
      <li>
        <div class="order-info">
          <p>
            小锅饭豆腐馆（全运店）
            <i class="fa fa-caret-down"></i>
          </p>
          <div class="order-info-right">
            <p>&#165;55</p>
            <div class="order-info-right-icon">去支付</div>
          </div>
        </div>
        <ul class="order-detailet">
          <li>
            <p>纯肉鲜肉（水饺） x 2</p>
            <p>&#165;15</p>
          </li>
          <li>
            <p>玉米鲜肉（水饺） x 1</p>
            <p>&#165;16</p>
          </li>
          <li>
            <p>配送费</p>
            <p>&#165;3</p>
          </li>
        </ul>
      </li>
    </ul>
    <h3>已支付订单信息：</h3>
    <ul class="order">
      <li>
        <div class="order-info">
          <p>
            万家饺子（软件园E18店）
            <i class="fa fa-caret-down"></i>
          </p>
          <div class="order-info-right">
            <p>&#165;49</p>
          </div>
        </div>
        <ul class="order-detailet">
          <li>
            <p>纯肉鲜肉（水饺） x 2</p>
            <p>&#165;15</p>
          </li>
          <li>
            <p>玉米鲜肉（水饺） x 1</p>
            <p>&#165;16</p>
          </li>
          <li>
            <p>配送费</p>
            <p>&#165;3</p>
          </li>
        </ul>
      </li>
      <li>
        <div class="order-info">
          <p>
            小锅饭豆腐馆（全运店）
            <i class="fa fa-caret-down"></i>
          </p>
          <div class="order-info-right">
            <p>&#165;55</p>
          </div>
        </div>
        <ul class="order-detailet">
          <li>
            <p>纯肉鲜肉（水饺） x 2</p>
            <p>&#165;15</p>
          </li>
          <li>
            <p>玉米鲜肉（水饺） x 1</p>
            <p>&#165;16</p>
          </li>
          <li>
            <p>配送费</p>
            <p>&#165;3</p>
          </li>
        </ul>
      </li>
    </ul>
    <FooterCompoent></FooterCompoent>>
  </div>>
</template>

<script>
export default {
name: "OrderList"
}
</script>

<style scoped>

</style>