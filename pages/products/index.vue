<template>
  <div>
    商品一覧<br>
    <table>
      <tr>
        <th>商品番号</th>
        <th>商品名</th>
        <th>詳細</th>
      </tr>
      <tr>
        <td>1</td>
        <td>商品1</td>
        <td><NuxtLink to="/products/1/show">詳細</NuxtLink></td>
      </tr>
      <tr>
        <td>2</td>
        <td>商品2</td>
        <td><NuxtLink to="/products/2/show">詳細</NuxtLink></td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
