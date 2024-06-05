<template>
  <div id="header">
    <div class="mfw-header">
      <div class="head-logo"></div>
      <ul class="head-nav">
        <li class="active">
          <NuxtLink to="/">首页</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index">目的地</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index">旅游攻略</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index">去旅游</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index">联系我们</NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
}

#header {
  .mfw-header {
    width: 1200px;
    height: 68px;
    margin: 0 auto;

    .head-nav {
      display: flex;

      li {
        list-style: none;

        a {
          display: inline-block;
          padding: 0 16px;
          line-height: 68px;
          text-decoration: none;
          color: #333;

          &:hover {
            color: #ff9d00;
            height: 65px;
            border-bottom: 3px solid #ff9d00;
          }
        }
      }

      li.active {
        a {
          background-color: #ff9d00;
          color: #fff
        }
      }
    }
  }
}
</style>