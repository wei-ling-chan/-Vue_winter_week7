<template>
  <h1>產品modal頁</h1>
  <label for="title" class="form-label">標題</label>
                  <input id="title" type="text" class="form-control" placeholder="請輸入標題" v-text="template.abc">
  <h3 >{{this.template.abc}}</h3>
  <img class="img-fluid" :src="this.template.imagesUrl" alt="">
</template>

<script>
export default {
  props: ['template']
}
</script>
