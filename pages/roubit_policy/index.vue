<template>
  <div class="privacy-policy">
    <div class="privacy-policy__block">
      <h2>Information gathering module and advertising Id</h2>
      <p>For the application to be delivered by our company, the following advertisement distribution companies may automatically acquire information of users for the purpose of advertisement distribution. There is NO personal identification from this information. Regarding information to be acquired, purposes of use, provision to third parties, etc., please confirm from the application · privacy policy link of the following advertisement distribution company.<br>
        AdMob（Google Inc.）<br>
        <a
          href="https://policies.google.com/technologies/ads?hl=ja"
          target="_blank">https://policies.google.com/technologies/ads</a>
      </p>
    </div>

    <div class="privacy-policy__block">
      <h2>情報収集モジュール, 広告IDについて</h2>
      <p>当社で配信するアプリでは、広告配信を目的として以下の広告配信事業者がご利用者の情報を自動取得する場合がございます。この情報から個人が特定されることはありません。取得する情報、利用目的、第三者への提供等につきましては、以下の広告配信事業者のアプリケーション・プライバシーポリシーのリンクよりご確認ください。<br>
        AdMob（Google Inc.）<br>
        <a
          href="https://policies.google.com/technologies/ads?hl=ja"
          target="_blank">https://policies.google.com/technologies/ads</a>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'static'
}
</script>

<style>
.privacy-policy {
  margin: 12px;
  font-family: sans;
}

.privacy-policy h1 {
  font-size: 30px;
}

.privacy-policy h2 {
  font-size: 20px;
}

.privacy-policy__block {
  background: #FAFAFA;
  padding: 12px 8px 12px;
  margin-top: 12px
}
</style>
