<template lang="pug">
  .deck
    v-app
      v-content
        p.display-2 デッキ一覧画面
        v-btn(color="primary") 新しいデッキを追加
        v-layout
          v-flex(xs12 sm6 offset-sm3)
            DeckPanel
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component({
  components: {
    DeckPanel: () => import('@/components/organisms/DeckPanel.vue')
  }
})
export default class TopPage extends Vue {
}
</script>
