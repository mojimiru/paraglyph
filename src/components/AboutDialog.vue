<script setup lang="ts">
import ParaglyphIcon from './ParaglyphIcon.vue'
</script>

<template>
  <q-card class="q-pa-md" style="width: 700px; max-width: 80vw;">
    <q-card-section align="left" class="q-pa-sm col-12 row">
      <span class="text-h5">
        <q-avatar square size="2rem"><ParaglyphIcon/></q-avatar>
        ぱらぐりふについて
      </span>
    </q-card-section>
    <q-separator/>
    <q-card-section align="left" class="q-pa-md col-12">
      <pre style="white-space: pre-wrap; font-family: sans-sarif;">ぱらぐりふ-ParaGlyph-は 日本語OK 商用OK なフォント試し書きサイトです。
画面上部の入力欄に好きな文字を入れるとそれぞれのフォントで表示されます。
気に入ったフォントがあればクリックして、配布ページからダウンロードしてくださいね！</pre>
    </q-card-section>
</q-card>
</template>
