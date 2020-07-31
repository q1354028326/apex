<template>
  <div style="padding-top:85px">
    <el-row :gutter="15" class="topmenu">
      <el-col :xs="20" :sm="10" :md="16" :lg="14" :xl="16" >
        <img src="../images/Logo.png" style="margin-left:50px;margin-top:17px;width:100px" />
      </el-col>
   
      <el-col :xs="0" :sm="6" :md="6" :lg="8" :xl="6">
        <ul class="topmenu-topul">
          <li>
            <i class="el-icon-s-home"></i>首页
          </li>
          <li>
            <i class="el-icon-s-flag"></i>足迹
          </li>
          <li>
            <i class="el-icon-s-order"></i>留言板
          </li>
          <li>
            <i class="el-icon-s-promotion"></i>友情链接
          </li>
          <li>
            <i class="el-icon-info"></i>关于博主
          </li>
        </ul>
      </el-col>
      <el-col :xs="2" :sm="1" :md="1" :lg="1" :xl="1">
        <div
          @click="drawer = true"
          style="border-radius: 100%;height:40px;width:40px;background-color:#dee1e9;margin-right:65px;text-align:center;line-height:40px;color:#768193;margin-top:12px"
        >
          <i class="el-icon-search"></i>
        </div>
      </el-col>
    </el-row>
    <div>
      <el-carousel height="350px" style="width:93%;margin:auto;border-radius: 10px">
        <el-carousel-item
          style="background:url(https://cdn.fengwanqing.xin/wp-content/uploads/2020/03/1584157653-2.jpg)no-repeat;background-size:100% ;background-attachment:fixed; "
        >
          <div class="content">
            <p>
              <template>
                <el-carousel
                  indicator-position="none"
                  :interval="4000"
                  type="card"
                  height="200px"
                  style="float:right;width:40%;margin-top:70px;margin-right:100px"
                >
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/tad3mum4o3ltad3mum4o3l.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hhv45o5shfvhhv45o5shfv.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hro5jamoczchro5jamoczc.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                </el-carousel>
              </template>
            </p>
          </div>
        </el-carousel-item>
        <el-carousel-item
          style="background:url(https://cdn.fengwanqing.xin/wp-content/uploads/2020/03/1584157655-5.jpg)no-repeat;background-size:100% ;background-attachment:fixed; "
        >
          <div class="content">
            <p>
              <template>
                <el-carousel
                  indicator-position="none"
                  :interval="4000"
                  type="card"
                  height="200px"
                  style="float:right;width:40%;margin-top:70px;margin-right:100px"
                >
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/tad3mum4o3ltad3mum4o3l.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hhv45o5shfvhhv45o5shfv.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hro5jamoczchro5jamoczc.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                </el-carousel>
              </template>
            </p>
          </div>
        </el-carousel-item>
        <el-carousel-item
          style="background:url(https://cdn.fengwanqing.xin/wp-content/uploads/2020/03/1584157654-3.jpg)no-repeat;background-size:100% ;background-attachment:fixed; "
        >
          <div class="content">
            <p>
              <template>
                <el-carousel
                  indicator-position="none"
                  :interval="4000"
                  type="card"
                  height="200px"
                  style="float:right;width:40%;margin-top:70px;margin-right:100px"
                >
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/tad3mum4o3ltad3mum4o3l.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hhv45o5shfvhhv45o5shfv.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                  <el-carousel-item
                    style="background:url(https://img9.51tietu.net/pic/2019-091212/hro5jamoczchro5jamoczc.jpg)no-repeat;background-size:cover; "
                  ></el-carousel-item>
                </el-carousel>
              </template>
            </p>
          </div>
        </el-carousel-item>
      </el-carousel>
    </div>
    <div class="middiv">
      <ul class="middiv-ul">
        <a href="#">
        <li class="liselt">
          <i class="el-icon-cpu"></i>智能推荐
        </li>
        </a>
        <li>
          <i class="el-icon-notebook-2"></i>全部文章
        </li>
        <li>
          <i class="el-icon-ship"></i>实用分享
        </li>
        <li>
          <i class="el-icon-reading"></i>劲草诗集
        </li>
        <li>
          <i class="el-icon-notebook-1"></i>读书笔记
        </li>
        <li>
          <i class="el-icon-video-play"></i>短片
        </li>
      </ul>
    </div>
    <div>
      <el-row :gutter="20" style="width:93%;margin:auto;margin-top:15px">
        <el-col :xs="70" :sm="15" :md="16" :lg="18" :xl="19">
          <el-row :gutter="20">
            <el-col :xs="24" :sm="12" :md="12" :lg="8" :xl="6">
              <div class="grid-content bg-purple miditem"></div>
            </el-col>
            <el-col :xs="24" :sm="12" :md="12" :lg="8" :xl="6">
              <div class="grid-content bg-purple-light miditem"></div>
            </el-col>
            <el-col :xs="24" :sm="12" :md="12" :lg="8" :xl="6">
              <div class="grid-content bg-purple miditem"></div>
            </el-col>
            <el-col :xs="24" :sm="12" :md="12" :lg="8" :xl="6 ">
              <div class="grid-content bg-purple-light miditem"></div>
            </el-col>
          </el-row>
        </el-col>
        <el-col :xs="0" :sm="6" :md="8" :lg="6" :xl="5">
          <div style="overflow: hidden;">
            <img
              style="float:left;height:80px;width:80px;border-radius: 10px;box-shadow: 7px 2px 7px #cfcfcf;"
              src="http://q.qlogo.cn/headimg_dl?bs=qq&dst_uin=1354028326&src_uin=www.qqjike.com&fid=blog&spec=100"
            />
            <div style="float:left">
              <div style="color:#475669;font-size:20px;padding-left:20px;padding-top:10px">TwoDog</div>
              <div style="color:#475669;font-size:17px;padding-left:20px">一个什么活都能整的白给青年</div>
            </div>
          </div>
          <div style="margin-top:15px;color:#475669">关注我</div>
          <div
            style="height:2px;background-color:#5faaff;margin-top:5px;margin-bottom:20px;overflow: hidden;"
          >
            <div
              style="float:left;width:5%;height:2px;background-color:#5faaff;box-shadow: 2px 2px 5px #5faaff;"
            ></div>
            <div
              style="float:left;width:95%;height:2px;background-color:#e0e0e0;box-shadow: 8px 2px 5px #e0e0e0;"
            ></div>
          </div>
          <div>
            <a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=1354028326&site=qq&menu=yes">
              <img
                border="0"
                src="http://wpa.qq.com/pa?p=2:1354028326:51"
                alt="点击这里给我发消息"
                title="点击这里给我发消息"
              />
            </a>
          </div>
          <div style="margin-top:15px;color:#475669">心情</div>
          <div
            style="height:2px;background-color:#5faaff;margin-top:5px;margin-bottom:20px;overflow: hidden;"
          >
            <div
              style="float:left;width:5%;height:2px;background-color:#5faaff;box-shadow: 2px 2px 5px #5faaff;"
            ></div>
            <div
              style="float:left;width:95%;height:2px;background-color:#e0e0e0;box-shadow: 8px 2px 5px #e0e0e0;"
            ></div>
          </div>
          <div>
            <el-steps direction="vertical" :active="1" style="height:300px">
              <el-step title="2020-7-30 Python多线程实战" description="整天就知道爬爬爬 爪巴 亻尔 女马"></el-step>
              <el-step title="2020-7-29 Python进度条" description="拉胯模拟器"></el-step>
              <el-step title="2020-7-28 今天也是摸鱼的三天呢" description="墨鱼更健康"></el-step>
              <el-step title="2020-7-27 今天也是摸鱼的两天呢" description="墨鱼更健康"></el-step>
              <el-step title="2020-7-26 今天也是摸鱼的一天呢" description="墨鱼更健康"></el-step>
            </el-steps>
          </div>
          <div style="margin-top:15px;color:#475669">博客统计</div>
          <div
            style="height:2px;background-color:#5faaff;margin-top:5px;margin-bottom:20px;overflow: hidden;"
          >
            <div
              style="float:left;width:5%;height:2px;background-color:#5faaff;box-shadow: 2px 2px 5px #5faaff;"
            ></div>
            <div
              style="float:left;width:95%;height:2px;background-color:#e0e0e0;box-shadow: 8px 2px 5px #e0e0e0;"
            ></div>
          </div>
          <div>
            <el-badge :value="1" class="item" type="primary">
              <el-button size="small">评论</el-button>
            </el-badge>
            <el-badge :value="2" class="item" type="warning">
              <el-button style="margin-left:10px" size="small">回复</el-button>
            </el-badge>
            <el-badge :value="1" class="item" type="danger ">
              <el-button style="margin-left:10px" size="small">点赞</el-button>
            </el-badge>
            <el-badge :value="2" class="item" type="info">
              <el-button style="margin-left:10px" size="small">关注</el-button>
            </el-badge>
          </div>
        </el-col>
      </el-row>
    </div>
    <div class="snow-container"></div>
    <el-drawer title="我是标题" :visible.sync="drawer" :with-header="false">
      <span>搜索功能暂时还没有喔~</span>
    </el-drawer>
  </div>
</template>
   

<script>
export default {
  data() {
    return {
      drawer: false,
    };
  },
  methods: {
    reverseMessage: function () {
      
    },
  },
  created: function () {
    console.log(
      "%c 你敢抄我博客头给你砸肚子里 =}}=========>",
      " text-shadow: 0 1px 0 #ccc,0 2px 0 #c9c9c9,0 3px 0 #bbb,0 4px 0 #b9b9b9,0 5px 0 #aaa,0 6px 1px rgba(0,0,0,.1),0 0 5px rgba(0,0,0,.1),0 1px 3px rgba(0,0,0,.3),0 3px 5px rgba(0,0,0,.2),0 5px 10px rgba(0,0,0,.25),0 10px 10px rgba(0,0,0,.2),0 20px 20px rgba(0,0,0,.15);font-size:5em"
    );
    var OriginTitile = document.title;
    var titleTime;
    document.addEventListener("visibilitychange", function () {
      if (document.hidden) {
        document.title = "WDNM有种别跑！(•́へ•́╬)";
        clearTimeout(titleTime);
      } else {
        document.title = "回来就好,乖乖的喔~(#^.^#)";
        titleTime = setTimeout(function () {
          document.title = OriginTitile;
        }, 2000);
      }
    });
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.topmenu {
  z-index: 2000;
  background-color: rgba(255, 255, 255, 0.8);
  position: fixed;
  top: 0px;
  border-bottom: 1px #d9e0ea solid;
  height: 65px;
  width: 100%;
  overflow: hidden;
}
.topmenu-topul {
  height: 65px;
  margin-right: 30px;
  color: #768193;
  overflow: hidden;
}
.topmenu-topul li {
  list-style: none;
  height: 65px;
  line-height: 65px;
  font-size: 15px;
  float: left;
  margin-left: 20px;
}
.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 150px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
.content {
  height: 100%;
  width: 100%;
  background: inherit;
}
.content p {
  z-index: 1;
  color: #000;
  position: relative;
  margin: 0;
}
.content::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: inherit;
  filter: blur(10px);
}
.snow-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 100001;
}
.middiv {
  height: 35px;
  width: 93%;
  margin: auto;
  margin-top: 15px;
}
.middiv-ul {
  height: 35px;
  color: #475669;
  font-size: 14px;
  line-height: 35px;
}
.middiv-ul li {
  list-style: none;
  line-height: 40px;
  height: 35px;
  line-height: 35px;
  font-size: 15px;
  float: left;
  margin-right: 5px;
  border-radius: 20px;
  padding-left: 5px;
  padding-right: 5px;
}
.liselt {
  background-color: #4e9fff;
  box-shadow: 2px 2px 10px #4e9fff;
  color: #fff;
}
.middiv-ul li:hover {
  background-color: #dae4f3;
}

.el-col {
  border-radius: 4px;
}
.bg-purple-dark {
  background: #99a9bf;
}
.bg-purple {
  background: #d3dce6;
}
.bg-purple-light {
  background: #e5e9f2;
}
.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
.row-bg {
  padding: 10px 0;
  background-color: #f9fafc;
}
.miditem {
  height: 350px;
  margin-bottom: 20px;
  box-shadow: 2px 5px 10px #e2e2e2;
}
.mid-right {
  width: 21.5%;
  margin-left: 1.5%;
}

</style>
