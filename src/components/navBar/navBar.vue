<template>
  <div id="header">
    <div id="page_top">
      <div class="bg_warp">
        <div class="bg"></div>
        <div class="mask"></div>
      </div><!--bg_warp-END-->
      <div class="header-top">
        <div class="page-width clearfix"><!--左右导航的box-->
          <div class="header_top_nav">
            <ul>
              <li class="item item-home"><a href="#">主站</a></li>
              <li class="item"><a href="#">画友</a></li>
              <li class="item">
                <a href="#">游戏中心</a>
                <div class="game-center header-hover"><!--  外层   -->
                  <div class="c clearfix"><!--  里层   -->
                    <div class="fl"><!--  游戏中心左边   -->
                      <div class="imgbox">
                        <a href="#">
                          <img src="../../assets/image/cont/game-center__img1.jpg" alt="#">
                          <span>命运-冠位指定（Fate/GO）</span>
                        </a>
                      </div> 
                       <div class="game-img">
                        <a href="#">
                          <img src="../../assets/image/cont/game_img1.png" alt="#">
                          <span>刀剑乱舞</span>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/game_img2.png" alt="#">
                          <span>刀剑乱舞</span>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/game_img3.jpg" alt="#">
                          <span>刀剑乱舞</span>
                        </a>
                      </div>
                    </div>
                    <div class="fr"><!--  游戏中心右边   -->
                      <div class="game-list">
                       
                        <div class="title">
                          <i></i>
                          <a href="#">游戏论坛</a>
                        </div>
                        <div class="all">
                          <a href="#">仙剑奇侠传幻璃镜</a>
                          <a href="#">魔法禁书目录</a>
                          <a href="#">萌王EX</a>
                          <a href="#">妖精的衣橱</a>
                          <a href="#">神代梦华谭</a>
                          <a href="#">碧蓝航线</a>
                          <a href="#">光明大陆</a>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div id="gameImg"></div><!--  ？？？   -->
                </div>
                </li>
              <li class="item">
                <a href="#">直播</a>
                <div class="live-box header-hover">
                  <div class="live-box__c">
                    <div class="fl">
                      <div class="title">热门直播:</div>
                      <div class="cont">
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img6.jpg" alt="#">
                          <i>LIVE</i>
                          <p>热爱电竞の三三</p>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img2.jpg" alt="#">
                          <i>LIVE</i>
                          <p>大角虫漫画</p>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img3.jpg" alt="#">
                          <i>LIVE</i>
                          <p>木本青</p>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img4.gif" alt="#">
                          <i>LIVE</i>
                          <p>一只小鹿噜噜噜</p>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img2.jpg" alt="#">
                          <i>LIVE</i>
                          <p>污叶妹屮</p>
                        </a>
                        <a href="#">
                          <img src="../../assets/image/cont/live-box__img6.jpg" alt="#">
                          <i>LIVE</i>
                          <p>污污_永远的魔法师_</p>
                        </a>
                      </div><!--  内容   -->
                    </div>
                    
                    <div class="fl">
                      <div class="title">热门直播:</div>
                    </div>
                  </div>
                </div>
                </li>
              <li class="item"><a href="#">周边</a></li>
              <li class="item">
                <a href="#">移动端</a>
                <div class="header-app header-hover">
                  <i></i>
                </div>
                </li>
            </ul>
          </div><!--header_top_nav-END-->
          <div class="header-top__user"><!--  herder-top右边   -->
            <div class="login-box">
              <a href="#">登录</a>
              <span></span>
              <a href="#">注册</a>
            </div>
            <div class="user-post">
              <a href="#" class="link">投 稿</a>
              <div class="user-post__hover header-hover">
                <a href="#" class="post">视频投稿</a>
                <a href="#" class="manage">投稿管理</a>
                <a href="#" class="create">创作中心</a>
              </div>
            </div>
          </div><!--header-top__user-END-->
        </div><!--page-width clearfix-END-->
      </div><!--header-top-END-->
    </div>
    <div class="header-c"><!---   header外层    -->
      <div class="page-width"><!---   header内层    -->
        <a href="#" id="header_logo"></a>
        <p id="header_title"></p>
        <div id="search" class="clearfix"><!---   搜索    -->
          <div class="search-rank">排行榜</div>
          <div class="search-box">
            <input type="text" class="text" placeholder="Search here...">
            <a href="#" class="btn"><i></i></a>
            <div class="search-history">
              <div class="title">历史搜索</div>
              <div class="list">
                <a href="#">努巴尼欢乐秀<i></i></a>
                <a href="#">主播真会玩守望篇<i></i></a>
                <a href="#">主播真会玩女神篇<i></i></a>
                <a href="#">暴暴勺暴暴<i></i></a>
                <a href="#">OverWatch<i></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="header-title">哔哩哔哩 (゜-゜)つロ 干杯~</div>
      </div>
    </div>
  </div>
</template>

<script>
import $ from 'jquery'
export default {
  name:'navBar'
}
</script>

<style>
@import '../../assets/css/base.css';
</style>