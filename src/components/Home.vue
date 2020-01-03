<template>
  <div class="Home">
    <div class="top">
      <div class="top-left">
        <p><i class="iconfont icon-gengduo"></i>YOHO!BUY 有货</p>
          <ul class="top-list">
            <li>YOHUO</li>
            <li>YOHUO</li>
            <li>YOHUO</li>
            <li>YOHUO</li>
            <li>YOHUO</li>
          </ul>
      </div>
      <div class="hint">
        <span>!</span>
        <span>
          关于防诈骗的重要提醒
        </span>
      </div>
      <p class="login">
        Hi ~
        <span>[请登录]</span>
        <span>[请注册]</span>
      </p>
      <ul class="list">
        <li>|<span>MY有货<i class="iconfont icon-xjt"></i></span></li>
        <li>|<span><i class="iconfont icon-dingdan"></i>我的订单</span></li>
        <li>|<span><i class="iconfont icon-faxian"></i>我的收藏</span></li>
        <li>|<span><i class="iconfont icon-xiaoxi"></i>消息</span></li>
        <li>|<span><i class="iconfont el-icon-key"></i>客户服务</span></li>
        <li>|<span><i class="iconfont icon-weixin"></i>关注有货</span></li>
        <li>|<span><i class="iconfont icon-shouji"></i>手机版</span></li>
      </ul>
    </div>
    <div class="nav">
      <ul class="nav-list">
        <li>
          <p>男生</p>
          <p>BOY</p>
        </li>
        <li>
          <p>女生</p>
          <p>GIRLS</p>
        </li>
        <li>
          <p>潮童</p>
          <p>KIDS</p>
        </li>
        <li>
          <p>创意生活</p>
          <p>LIFE STYLE</p>
        </li>
      </ul>
      <h1 class="logo">
      </h1>
      <div class="nav-left">
        <input type="text" class="search" placeholder="满399减100，最高可减1000">
        <div class="search-btn"><i class="iconfont icon-fangdajing"></i></div>
        <i class="iconfont icon-gwc"></i>
        <div class="type">
          <ul>
            <li>卫衣</li>
            <li>牛仔裤</li>
            <li>运动鞋</li>
            <li>椰子</li>
            <li>nike</li>
            <li>欧文</li>
          </ul>
        </div>
      </div>
      <ul class="nav-box">
        <li>新品到着</li>
        <li>品牌一览</li>
        <li>服饰</li>
        <li>鞋履</li>
        <li>包袋</li>
        <li>配饰 · 其他</li>
        <li>逛</li>
        <li>SALE</li>
        <li>证照/协议</li>
      </ul>
      <div class="box"></div>
    </div>

    <swiper :options="swiperOption" class="banner">
    <swiper-slide>
      <img src="../assets/images/banner1.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/images/banner2.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/images/banner3.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/images/banner4.jpg" alt="">
    </swiper-slide>
  </swiper>
          <ul class="img-bottom">
      <li>
        <img src="//img10.static.yhbimg.com/yhb-img01/2020/01/02/11/01ff0d41611fbd03b5e3d42b3c041dcd8a.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img11.static.yhbimg.com/yhb-img01/2020/01/02/11/01687e2e1c9dce628e430a030e30d98bb1.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img11.static.yhbimg.com/yhb-img01/2020/01/02/11/012ca6d990dcf776e264d38ababd9651c4.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img11.static.yhbimg.com/yhb-img01/2020/01/02/11/01b4e9b073ebff2860761d2bda15275606.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img11.static.yhbimg.com/yhb-img01/2020/01/02/11/0129439fcc1258566a7daa82280f4a3e8f.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img10.static.yhbimg.com/yhb-img01/2020/01/02/11/01d1456f4040584d7df71f2ae71d5580ae.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img10.static.yhbimg.com/yhb-img01/2020/01/02/11/0109757b071f1ce46d8edb9e4159f9b0e4.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
      <li>
        <img src="//img10.static.yhbimg.com/yhb-img01/2020/01/02/11/0155d4a3ce1a3d63a1c0e5eb12243b549b.jpg?imageView2/2/w/138/h/54" alt="">
      </li>
    </ul>
    <div class="main">
      <h2>人气单品</h2>
      <div class="clothing">
        <img src="../assets/images/clothing1.jpg" alt="">
        <img src="../assets/images/clothing2.jpg" alt="">
        <img src="../assets/images/clothing3.jpg" alt="">
        <img src="../assets/images/clothing1.jpg" alt="">
        <img src="../assets/images/clothing3.jpg" alt="">
        <img src="../assets/images/clothing1.jpg" alt="">
        <img src="../assets/images/clothing3.jpg" alt="">
        <img src="../assets/images/clothing1.jpg" alt="">
        <img src="../assets/images/clothing3.jpg" alt="">
        <img src="../assets/images/clothing2.jpg" alt="">
      </div>
      <h2>优选品牌</h2>
      <div class="brand ">
        <img src="../assets/images/brand1.jpg" alt="">
        <img src="../assets/images/brand2.jpg" alt="">
        <img src="../assets/images/brand3.jpg" alt="">
        <img src="../assets/images/brand4.jpg" alt="">
        <img src="../assets/images/brand5.jpg" alt="">
        <img src="../assets/images/brand6.jpg" alt="">
        <img src="../assets/images/brand7.jpg" alt="">
        <img src="../assets/images/brand8.jpg" alt="">
        <img src="../assets/images/brand4.jpg" alt="">
        <img src="../assets/images/brand5.jpg" alt="">
        <img src="../assets/images/brand6.jpg" alt="">
        <img src="../assets/images/brand7.jpg" alt="">
        <img src="../assets/images/brand8.jpg" alt="">
        <img src="../assets/images/brand4.jpg" alt="">
        <img src="../assets/images/brand5.jpg" alt="">
      </div>
      <h2>时尚鞋履</h2>
      <div class="shoes ">
        <img src="../assets/images/shoes.jpg" alt="">
        <img src="../assets/images/shoes2.jpg" alt="">
        <img src="../assets/images/shoes3.jpg" alt="">
        <img src="../assets/images/shoes3.jpg" alt="">
        <img src="../assets/images/shoes3.jpg" alt="">
        <img src="../assets/images/shoes.jpg" alt="">
        <img src="../assets/images/shoes2.jpg" alt="">
        <img src="../assets/images/shoes3.jpg" alt="">
        <img src="../assets/images/shoes.jpg" alt="">
        <img src="../assets/images/shoes.jpg" alt="">
        <img src="../assets/images/shoes4.jpg" alt="">
        <img src="../assets/images/shoes4.jpg" alt="">
        <img src="../assets/images/shoes4.jpg" alt="">
        <img src="../assets/images/shoes4.jpg" alt="">
        <img src="../assets/images/shoes4.jpg" alt="">
      </div>
      <h2>潮人配饰</h2>
      <div class="Acc ">
        <img src="../assets/images/Acc1.jpg" alt="">
        <img src="../assets/images/Acc2.jpg" alt="">
        <img src="../assets/images/Acc3.jpg" alt="">
        <img src="../assets/images/Acc4.jpg" alt="">
        <img src="../assets/images/Acc5.jpg" alt="">
        <img src="../assets/images/Acc1.jpg" alt="">
        <img src="../assets/images/Acc2.jpg" alt="">
        <img src="../assets/images/Acc3.jpg" alt="">
        <img src="../assets/images/Acc4.jpg" alt="">
        <img src="../assets/images/Acc5.jpg" alt="">
        <img src="../assets/images/Acc6.jpg" alt="">
        <img src="../assets/images/Acc6.jpg" alt="">
        <img src="../assets/images/Acc6.jpg" alt="">
        <img src="../assets/images/Acc6.jpg" alt="">
        <img src="../assets/images/Acc6.jpg" alt="">
      </div>
      <h2>新品上架</h2>
      <div class="new ">
        <ul>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥599.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥599.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥599.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥599.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new4.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
                    <li>
            <img src="../assets/images/new6.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new4.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new5.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new6.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new7.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
                    <li>
            <img src="../assets/images/new9.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new7.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new8.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new9.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new10.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
                    <li>
            <img src="../assets/images/new12.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new10.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new11.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new12.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new15.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
                    <li>
            <img src="../assets/images/new13.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new14.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new14.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new15.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new15.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
                    <li>
            <img src="../assets/images/new14.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>

          <li>
            <img src="../assets/images/new13.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new15.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new14.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new4.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new2.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new3.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥169.00</p>
          </li>
          <li>
            <img src="../assets/images/new1.jpg" alt="">
            <p>corade 培根酱臭妹妹印花短袖T恤</p>
            <p>¥599.00</p>
          </li>

        </ul>
      </div>
      <div class="more">
        查看更多
      </div>
    </div>
    <div class="bottom">
      <div class="footer-top">
      <div class="left">
        <span>100%</span>
        <span>正品</span>
      </div>
      <div class="left">
        <span>7天</span>
        <span>无理由退货</span>
      </div>
      <div class="left">
        <span>便捷</span>
        <span>在线客服</span>
      </div>
      </div>
      <div class="bottom-content">
        <ul>
          <li>
            <p>新手专区</p>
            <p>注册登录</p>
            <p>购物结算</p>
            <p>下单支付</p>
            <p>收货评价</p>
          </li>
          <li>
            <p>会员中心</p>
            <p>会员制度</p>
            <p>会员优惠</p>
            <p>账户管理</p>
            <p>密码管理</p>
          </li>
          <li>
            <p>购物指南</p>
            <p>发票</p>
            <p>尺码对照</p>
            <p>尺码解读</p>
            <p>商品咨询</p>
          </li>
          <li>
            <p>支付方式</p>
            <p>在线支付</p>
            <p>货到付款</p>
            <p>分期支付</p>
            <p>优惠券、有货币</p>
          </li>
          <li>
            <p>配送方式</p>
            <p>配送说明</p>
            <p>运费说明</p>
            <p>验货签收</p>
            <p>收货样品</p>
          </li>
          <li>
            <p>售后服务</p>
            <p>退换货政策</p>
            <p>退换货流程</p>
            <p>投诉与建议</p>
            <p>在线客服</p>
          </li>
          <li>
            <p>APP常见问题</p>
            <p>IPhone版</p>
            <p>Android版</p>
            <p>wap版</p>
            <p>IPAD版</p>
          </li>
        </ul>
      </div>
      <div class="footer-box">
        <div class="box-left">
          <img src="../assets/images/tu2.png" alt="">
          <img src="../assets/images/tu.png" alt="">
          <img src="../assets/images/tu2.png" alt="">
        </div>
        <div class="box-right">
          <a href="//www.yohobuy.com">返回首页</a>
          <span>|</span>
          <a href="//www.yohobuy.com">YOHO!BUY 有货</a>
          <span>|</span>
          <a href="//www.yohobuy.com">新力传媒</a>
          <span>|</span>
          <a href="//www.yohobuy.com">联系我们</a>
          <span>|</span>
          <a href="//www.yohobuy.com">商家入驻</a>
          <span>|</span>
          <a href="//www.yohobuy.com">隐私条款</a>
          <span>|</span>
          <a href="//www.yohobuy.com">友情链接</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流品类大全</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流资讯</a>
          <span>|</span>
          <a href="//www.yohobuy.com">穿衣搭配(男生版)</a>
          <span>|</span>
          <a href="//www.yohobuy.com">友情链接</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流品类大全</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流资讯</a>
          <span>|</span>
          <a href="//www.yohobuy.com">穿衣搭配(男生版)</a>
          <span>|</span>
          <a href="//www.yohobuy.com">穿衣搭配(男生版)</a>
          <span>|</span>
          <a href="//www.yohobuy.com">友情链接</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流品类大全</a>
          <span>|</span>
          <a href="//www.yohobuy.com">潮流资讯</a>
          <span>|</span>
          <a href="//www.yohobuy.com">穿衣搭配(男生版)</a>
          <span>|</span>
          <a href="//www.yohobuy.com">穿衣搭配(男生版)</a>
          <span>|</span>
          <a href="//www.yohobuy.com">友情链接</a>
          <span>|</span>
        </div>
      </div>
    </div>
  </div>
</template>
      
<script>
export default {
  data() {
    return {};
  }
};
</script>
         
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.top {
  background: #f4f4f4;
  height: 32px;
}
.top p {
  width: 120px;
  font-size: 12px;
  margin-left: 56px;
  line-height: 32px;
  color: #000000;
}
.icon-gengduo {
  font-size: 12px;
  margin-right: 5px;
  color: #cccccc;
}
.top-list {
  width: 188px;
  background: #f4f4f4;
  height: 160px;
  margin-left: 56px;
  padding-left: 20px;
  display: none;
}
.top-list li {
  line-height: 24px;
}
.top-left {
  float: left;
}
/* 提示 */
.hint {
  width: 142px;
  float: left;
  height: 32px;
  overflow: hidden;
  margin-left: 20px;
  margin-right: 60px;
}
.hint span {
  line-height: 32px;
  font-size: 12px;
  color: #d71d32;
}
/* 登录 */
.login {
  float: left;
  margin-left: 50px;
}
.list {
  float: left;
}
.list li {
  float: left;
  line-height: 32px;
  color: #8e8e8e;
  font-size: 12px;
}
.list li span {
  margin: 0 10px;
}
.icon-xjt {
  font-size: 12px;
}
.icon-dingdan {
  font-size: 12px;
}
.icon-faxian {
  font-size: 12px;
}
.icon-xiaoxi {
  font-size: 12px;
}
.el-icon-key {
  font-size: 12px;
}
.icon-weixin {
  font-size: 12px;
}
.icon-shouji {
  font-size: 12px;
}
.nav {
}
.nav-list {
  width: 344px;
  height: 90px;
  padding-top: 35px;
  margin-left: 56px;
  float: left;
}
.nav-list li {
  float: left;
  padding: 10px 20px;
}
.nav-list li:nth-child(1) {
  background: #3a3a3a;
  color: #ffffff;
}
.nav-list li p {
  text-align: center;
}
/* 搜索 */
.nav-left {
  width: 396px;
  height: 50px;
  float: left;
  margin-top: 40px;
  margin-left: 120px;
}
.search {
  width: 220px;
  height: 26px;
  padding-left: 20px;
  float: left;
}
.search-btn {
  width: 78px;
  height: 26px;
  float: left;
  background: #3a3a3a;
  text-align: center;
  line-height: 26px;
}
.icon-fangdajing {
  color: #ffffff;
}
.logo {
  width: 182px;
  height: 53px;
  background: #8e8e8e;
  float: left;
  margin-top: 22px;
  margin-left: 80px;
}
.icon-gwc {
  font-size: 20px;
  color: #3a3a3a;
  margin-left: 25px;
  line-height: 26px;
}
.type {
  width: 320px;
  height: 16px;
  margin-top: 5px;
}
.type ul li {
  float: left;
  color: #b0b0b0;
  margin-right: 18px;
  line-height: 16px;
  font-size: 12px;
}
.type ul li:hover {
  color: red;
}
.nav-box {
  width: 100%;
  padding-left: 56px;
  height: 40px;
  float: left;
  background: #3a3a3a;
  border: 0;
}
.nav-box li {
  margin-right: 82px;
  float: left;
  line-height: 40px;
  font-size: 14px;
  color: #ffffff;
}
.box {
  height: 130px;
}
.banner {
  width: 1150px;
  height: 450px;
}
.img-bottom {
  width: 100%;
  padding: 0 56px;
  height: 54px;
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}
.img-bottom li {
  height: 54px;
}
.main h2 {
  margin: 80px 492px 0 492px;
  width: 300px;
  height: 33px;
  border: 2px solid #000000;
  font-size: 16px;
  text-align: center;
  line-height: 33px;
}
.clothing {
  padding-top: 40px;
  margin: 0 56px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-between;
  height: 560px;
}
.brand {
  padding-top: 40px;
  margin: 0 56px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-around;
  height: 416px;
}
.shoes {
  padding-top: 40px;
  margin: 0 56px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-between;
  height: 850px;
}
.shoes img:nth-child(2) {
  height: 248px;
}
.shoes img:nth-child(7) {
  height: 248px;
}
.Acc {
  padding-top: 40px;
  margin: 0 56px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-between;
  height: 850px;
}
.Acc img:nth-child(2) {
  height: 248px;
}
.Acc img:nth-child(7) {
  height: 248px;
}
.new ul li img {
  width: 222px;
  height: 298px;
}
.new ul {
  padding-top: 40px;
  margin: 0 56px;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-between;
  height: 4080px;
  margin-bottom: 60px;
}
.new ul li p {
  font-size: 12px;
  text-align: center;
  line-height: 22px;
  margin-top: 8px;
  color: #222222;
}
.more{
  width: 120px;
  height: 35px;
  margin: 0 571px 40px;
  background: #000000;
  color: #ffffff;
  line-height: 35px;
  text-align: center;
  font-size: 14px;
}
.bottom{
  height: 384px;
  background: #000000;
  padding: 0 56px;
}
.footer-top{
  height: 50px;
  padding-top:20px;
  padding-bottom: 10px;
  border-bottom: 1px solid #262626;
}
.left{
  float: left;
  font-size: 12px;
  margin-right: 60px;
}
.left span:nth-child(1){
  color: red;
  font-weight: 700;
}
.left span:nth-child(2){
  color: #ffffff;
  font-weight: 700;
}
.bottom-content{
  width: 100%;
  height: 120px;
  padding: 15px 0;
}
.bottom-content ul li{
  float: left;
  color: #666666;
  font-size: 12px;
  line-height: 24px;
  width: 164px;
  height: 151px;
}
.bottom-content ul li p:nth-child(1){
  color: #ffffff;
}
.box-left img{
  margin-right: 8px;
  float: left;
}
.box-left{
  float: left;
}
.footer-box{
  padding-top: 10px;
  height: 124px;
}
.box-right{
  font-size: 12px;
  margin-left: 130px;
  width: 700px;
  height: 60px;
  float: left;
  color: #666666;
  line-height: 20px;
}
.box-right span{
  padding: 0 10px;
}
</style>
