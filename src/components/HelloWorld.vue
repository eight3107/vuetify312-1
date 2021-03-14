<template>
  <v-app>
    <v-flex xs6 md12>
      <v-card>
        <v-card-title class="font-weight-bold pb-0">新規会員登録フォーム</v-card-title>
        <v-card-text>ああああああああああああああああああああああああああああああああああ</v-card-text>
        <v-card-title>稼働する条件や、空き状況</v-card-title>
        <v-list class="pb-2">
          <v-btn outlined rounded class="mr-2" color="green lighten-3">2万円〜</v-btn>
          <v-btn outlined rounded class="mr-2" color="green">2.5万円〜</v-btn>
          <v-btn outlined rounded class="mr-2" color="green">3万円〜</v-btn>
          <v-btn outlined rounded class="mr-2" color="green">3.5万円〜</v-btn>
          <v-btn outlined rounded class="mr-2" color="green">4万円〜</v-btn>
          <v-btn outlined rounded class="mr-2" color="green">それ以上</v-btn>
        </v-list>
        <v-card-title>稼働開始可能日時</v-card-title>
        <v-select class="px-2" solo type="datetime"></v-select>
          <v-card-title>簡単にアピールポイント教えてください。</v-card-title>
          <v-textarea
            class="mt-0"
            solo
            label="Solo textarea"
            auto-grow
            rows="1"
            value=""
            placeholder="ああああああ"
          ></v-textarea>
      </v-card>
    </v-flex>
  </v-app>
</template>

<script>

</script>
