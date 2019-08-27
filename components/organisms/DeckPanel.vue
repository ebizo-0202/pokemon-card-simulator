<template lang="pug">
  v-card
    v-container(fill-height fluid)
      v-layout(fill-height)
        v-flex(xs12 align-end flexbox)
          span(class="headline") ジラーチサンダー
    v-card-title
      div
        span(class="grey--text") いっちー
    v-card-actions
      v-btn(class="ma-2" tile color="indigo" dark) このデッキを使う
      v-btn(class="ma-2" tile outlined color="success") #[v-icon(left) mdi-pencil] 編集
</template>
