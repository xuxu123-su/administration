<template>
  <Row :gutter="20">
<!--    echarts组件图引入-->
    <Col span="6">
      <Card>
        <total-sale/>
      </Card>
    </Col>
    <Col span="6">
      <Card>
        <total-orders/>
      </Card>
    </Col>
    <Col span="6">
      <Card>
        <today-user/>
      </Card>
    </Col>
    <Col span="6">
      <Card>
        <total-user/>
      </Card>
    </Col>
  </Row>
</template>

<script>
  import TotalSale from "@/components/TotalSale";
  import TotalOrders from "@/components/TotalOrders";
  import TodayUser from "@/components/TodayUser";
  import TotalUser from "@/components/TotalUser";

  export default {
    name: "index",
    components: {
      TotalSale,
      TotalOrders,
      TodayUser,
      TotalUser,
    }
  }
</script>

<style scoped>

</style>
