<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
    
  </div>
  <InputPage></InputPage>
  <FunctionPage></FunctionPage>
</template>


<script>
export default {
    name: 'HtmlComponent',
    component: {
        InputPage
    },
    component: {
      FunctionPage
    },

    data() {
        return {
            title: '390 ศักดิ์นรินทร์ ม่วงศิริ',
        };
    },
    components: { InputPage,FunctionPage },

}
import FunctionPage from 'src/pages/FunctionPage.vue';
import InputPage from 'src/pages/InputPage.vue';

</script>

<style scoped></style>
