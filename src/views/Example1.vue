<script setup lang="ts">
import Border from '../components/BorderItem.vue'
</script>

<template>
  <div id="bodu">
    <h1 id="title">日比谷校舎模型</h1>
    <p id="location">第１室</p>

    <img src="./img/ex1.png" width="100%" id="image" />
    <p id="caption">日比谷校舎正面玄関前での卒業写真</p>
    <div id="description">
      <p>
        １９２９(昭和４)年の校舎移転を前に（一中が日比谷を離れる前年）、科研部員生徒（昭３卒･坂上治
        郎､昭５卒･磯村豊ほか）が制作した。正門正面に「講堂（２階）」、右に「唱歌教室」が立つ。右は司
        法省に接し、間口三十一間＊余、奥行百三十五間。奥には雨中体操場と武芸道場に挟まれて運動場
        が広がる。一中は１８９９(明治３２)年に築地から日比谷に移り、関東大震災６年後の１９２９年、日比谷を
        離れて永田町の現在地に移転した。戦後、菊地龍道校長の下、１９５０(昭和２５)年制定の新校名に、す
        でに日比谷を離れて久しいにもかかわらず、由緒ある所縁の地「日比谷」を用いたのである。<br />
        ＊一間＝約１.８㍍
      </p>
    </div>
  </div>
  <Border />

  <div style="margin: 25px">
    <RouterLink to="/">例1 </RouterLink><br />
    <RouterLink to="/ex2">例2 </RouterLink><br />
    <RouterLink to="/ex3">例3 </RouterLink>
  </div>
</template>

<style scoped>
#bodu {
  margin: 25px;
}

#title {
  text-align: center;
}

#location {
  text-align: end;
  padding-bottom: 20px;
}

#image {
  display: block;
  margin: 0 auto;
  border: 1px solid #000;
}

#caption {
  text-align: center;
  font-size: 90%;
  color: #666;
  padding-bottom: 20px;
}
</style>
