<template>
  <div class="warbler-fe">
    <h1 class="title">开源项目</h1>
    <div class="job">
      <div class="job-name">warbler-js</div>
      <div class="skill-list">
        <div class="skill">JavaScript</div>
        <div class="skill">ES6+</div>
        <div class="skill">VitePress</div>
      </div>
      <div class="project-info">
        <div class="left">
          <p>项目简介：</p>
        </div>
        <div class="right">
          <p>
            <span class="circle">·</span>整理了常用的 JS 方法，部分来源于开发经验，部分来源于网络。
          </p>
          <p><span class="circle">·</span>在线文档地址 http://www.warblerfe.top/warbler/js</p>
          <p><span class="circle">·</span>源码地址 https://github.com/alanhzw/warbler-js</p>
        </div>
      </div>
    </div>
    <div class="job">
      <div class="job-name">warbler-cli</div>
      <div class="skill-list">
        <div class="skill">Lerna</div>
        <div class="skill">Commander</div>
        <div class="skill">JavaScript</div>
        <div class="skill">ES6+</div>
        <div class="skill">VitePress</div>
      </div>
      <div class="project-info">
        <div class="left">
          <p>项目简介：</p>
        </div>
        <div class="right">
          <p>
            <span class="circle">·</span>一个脚手架工具，用于快速创建项目或生成一组相同结构的代码。
          </p>
          <p><span class="circle">·</span>在线文档地址 http://www.warblerfe.top/warbler/cli</p>
          <p><span class="circle">·</span>源码地址 https://github.com/alanhzw/warbler-cli</p>
        </div>
      </div>
    </div>
    <div class="job">
      <div class="job-name">Warbler-Fe</div>
      <div class="skill-list">
        <div class="skill">Vue3</div>
        <div class="skill">Typescript</div>
        <div class="skill">Github</div>
      </div>
      <div class="project-info">
        <div class="left">
          <p>项目简介：</p>
        </div>
        <div class="right">
          <p>
            <span class="circle">·</span>为了降低前端开发的难度，提升开发效率，网站将前端导航以及
            warbler-cli 和 warbler-js 的文档整合在一起；
          </p>
          <p>
            <span class="circle">·</span>通过监听 scroll
            事件及高度的计算，完成双向滚动的前端导航页面；
          </p>
          <p><span class="circle">·</span>通过 iframe 整合其它网站</p>
          <p><span class="circle">·</span>在线体验地址 http://www.warblerfe.top</p>
          <p><span class="circle">·</span>源码地址 https://github.com/alanhzw/warbler-fe</p>
        </div>
      </div>
    </div>
    <div class="job">
      <div class="job-name">相关链接</div>
      <div class="project-info">
        <div class="right">
          <p><span class="circle">·</span>Github https://github.com/alanhzw</p>
          <p><span class="circle">·</span>掘金社区 https://juejin.cn/user/4099422807393901/posts</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
.warbler-fe {
  margin-top: 32px;
  .title {
    font-size: 25px;
    margin-top: 0;
  }
  p {
    color: #666;
    margin: 8px 0;
  }
  .job {
    .job-name {
      font-size: 18px;
      font-weight: bold;
      margin: 8px 0;
    }
    .skill-list {
      display: flex;
      justify-content: flex-start;
      .skill {
        padding: 5px 10px;
        background-color: rgba(27, 31, 35, 0.05);
        margin: 10px 10px 5px 0;
        color: #333;
        border-radius: 4px;
        font-size: 13px;
      }
    }
    .project-info,
    .project-my {
      display: flex;
      justify-content: space-between;
      .left {
      }
      .right {
        flex: 1;
      }
    }
  }
}
</style>
