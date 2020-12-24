<template>
  <div>123456</div>
  <hr />
  <Button>1234</Button>
  <hr />
  <Switch v-model:value="switchValue" />
  <hr />
  <Tabs v-model:selected="Tabselected">
    <Tab title="tab1">内容1</Tab>
    <Tab title="tab2">内容2</Tab>
  </Tabs>
</template>

<script>
import { Button, Switch, Tabs, Tab } from "neko-ui-vue3";
import "neko-ui-vue3/dist/lib/neko.css";
export default {
  components: {
    Button,
    Switch,
    Tabs,
    Tab,
  },
  data() {
    return {
      switchValue: false,
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
