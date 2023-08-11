<template>
  <v-card>
    <v-layout>
      <v-navigation-drawer
        expand-on-hover
        rail
      >
        <v-list>
          <v-list-item
            prepend-avatar="../../images/drawing-illustration-anime-blue-hair-cartoon-Da-Capo-706145-wallhere.com.jpg"
            title="阿杨"
            subtitle="1351861548@qq.com"
          ></v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list density="compact" nav>
          <v-list-item prepend-icon="mdi-folder" title="我的文件" value="myfiles"></v-list-item>
          <v-list-item prepend-icon="mdi-account-multiple" title="Shared with me" value="shared"></v-list-item>
          <v-list-item prepend-icon="mdi-star" title="Starred" value="starred"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main style="height: 250px"></v-main>
    </v-layout>
  </v-card>
  <v-parallax src="../../images/drawing-illustration-anime-blue-hair-cartoon-Da-Capo-706145-wallhere.com.jpg">
    
  </v-parallax>
</template>

<style>
/** 普通指针样式**/
body {
    width: 100vw;
    height: 100vh;
    cursor: url('../../../arr33.png'), auto;
}

/** 链接指针样式**/
a:hover {
    cursor: url('../../../arr1.png'), pointer;
}
</style>
    <!--给WordPress网站添加鼠标点击爆炸五颜六色特效-->
    <canvas class="fireworks" style="position:fixed;left:0;top:0;z-index:99999999;pointer-events:none;"></canvas>
    <script type="text/javascript" src="djtx">
    import * as djtx from '../plugins/djtx.js'
  </script>