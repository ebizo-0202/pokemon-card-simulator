<template lang="pug">
  .deck
    p デッキ一覧画面
    v-app
      v-content
        v-btn(color="primary") 新しいデッキを追加
        v-layout
          v-flex(xs12 sm6 offset-sm3)
            v-card
              v-container(fill-height fluid)
                v-layout(fill-height)
                  v-flex(xs12 align-end flexbox)
                    span(class="headline") Top 10 Australian beaches
              v-card-title
                div
                  span(class="grey--text") Number 10
            v-card-actions
              v-btn(text color="orange") このデッキを使う
              v-btn(test color="orange") 編集
</template>

<script lang="ts">
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component
export default class TopPage extends Vue {
}
</script>
