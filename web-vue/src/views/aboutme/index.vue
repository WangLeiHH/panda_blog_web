<template>
  <div>
    <h2 style="text-align: center;">个人简介</h2>
    <p style="text-indent: 0px;">
        <img src="../1.jpg" alt="wl" style="border-radius:50%;width:100px;margin: 0 auto;">
    </p>
    <p style="text-align: center;">散落记忆里的时光</p>
    <p id="brief" style="text-align: center;">爱生活、。</p>
    <p
      id="brief"
      style="text-align: center;"
    >哪有什么岁月静好，不过是有人替你负重前行</p>
    <p style="text-align: center;">
      <a href="http://www.wangleihh.cn">
        <input
          type="button"
          value="了解更多"
          style="width: 310px; margin: 10px auto 0px; background-color: rgb(245, 138, 135); color: rgb(255, 255, 255); height: 40px; border: none; font-family: 'Microsoft Yahei'; font-size: 16px; letter-spacing: 2px;"
          onmouseover="this.style.backgroundColor='rgb(252, 125, 121)'"
          onmouseout="this.style.backgroundColor='#F58A87'"
        />
      </a>
    </p>
    <p style="text-align: center;"></p>

    <h2 style="text-align: center;margin-top:40px;margin-bottom:40px;">我的技能树</h2>
<section class="tech">
	<div class = "item">
		<div class = "describe">
			HTML/CSS/JS
		</div>
		<div class="progress">
		  <span class="green" style="width: 74%;"><span>74%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			C/C++
		</div>
		<div class="progress">
		  <span class="orange" style="width: 65%;"><span>65%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			PHOTOSHOP
		</div>
		<div class="progress">
		  <span class="red" style="width: 72%;"><span>72%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			JAVA
		</div>
		<div class="progress">
		  <span class="blue" style="width: 67%;"><span>67%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			PHP/MYSQL
		</div>
		<div class="progress">
		  <span class = "darkblue" style="width: 82%;"><span>82%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			COCOS2DX
		</div>
		<div class="progress">
		  <span class="orange" style="width: 75%;"><span>75%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			PYTHON
		</div>
		<div class="progress">
		  <span class="green" style="width: 58%;"><span>58%</span></span>
		</div>
	</div>
	<div class = "item">
		<div class = "describe">
			PR/AE
		</div>
		<div class="progress">
		  <span class="blue" style="width: 47%;"><span>47%</span></span>
		</div>
	</div>
 </section>

 <!-- contact -->
<h2 style="text-align: center; margin:20px">联系我</h2>
<div class = "icon-contact" style="margin:-2px auto;">
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip sinaweibo" title="" data-placement="top"><i class="fa fa-weibo"></i></a>
	</div>
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip tencentweibo" title="" data-placement="top"><i class="fa fa-tencent-weibo"></i></a>
	</div>
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip wechat" title="" data-placement="top"><i class="fa fa-weixin"></i></a>
	</div>
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip qq" title="" data-placement="top"><i class="fa fa-qq"></i></a>
	</div>
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip renren" title="" data-placement="top"><i class="fa fa-renren"></i></a>
	</div>
	<div class="col" id="icon">
		<a href="" target="_blank" class="social-icon tool-tip github" title="" data-placement="top"><i class="fa fa-github"></i></a>
	</div>
</div>

  </div>
</template>

<script>
export default {
  name: "",

  components: {},
  props: {},
  data() {
    return {};
  },
  watch: {},
  computed: {},
  methods: {},
  created() {},
  mounted() {}
};
</script>
 
<style scoped>
div{
	background-color: #fff;
}
div p{
        margin: 0 0 20px 0;
}

@media (min-width: 768px) {

	.icon-contact {
		height: 80px;
		margin: auto;
		width: 100%;
		max-width:700px;
	}
	.icon-contact .fa{
		line-height:70px;
		font-size: 35px;
		width: 70px;
	}
	.icon-contact .social-icon {
		display: inline-block;
		width: 70px;
		height: 70px;
		color: #fff;
		border-radius: 100%;
		margin: 6px;
		text-align: center;
		text-indent: 0px;
	}
	
}
@media (max-width: 768px) {
	.icon-contact {
		height: 60px;
		margin: auto;
		width: 100%;
		}
	.icon-contact .fa{
		line-height:50px;
		font-size: 20px;
		width: 50px;
	}
	.icon-contact .social-icon {
		display: inline-block;
		width: 50px;
		height: 50px;
		color: #fff;
		border-radius: 100%;
		margin: 6px;
		text-align: center;
		text-indent: 0px;
	}
}
/* body */
body{
	background-color:#fff;
	font-family:"Microsoft Yahei";
}

/* �罻������ɫ */
.icon-contact .sinaweibo{
	background-color: #EC5B5B;
}
.icon-contact .tencentweibo{
	background-color: #2BC0B5;
}
.icon-contact .wechat{
	background-color: #49C085;
}
.icon-contact .qq{
	background-color: #6F92FF;
}
.icon-contact .renren{
	background-color: #7243D4;
}
.icon-contact .github{
	background-color: #7782D1;
}
.icon-contact a{
	color:#fff !important;
}
.icon-contact #icon{
		float:left;
}
.icon-contact .col {
	width: 16.666667%;
	float:left;
	position: relative;
	min-height: 1px;
}
.icon-contact{
max-width:700px;
margin:auto;
text-indent:0px;
}
.friend-link a{
color:#00a67c !important;
}
.tech{
	max-width:700px;
	margin:auto;
 }
 .tech .item{
	width:100%;
	clear:both;
	margin-right:auto;
	margin-left:auto;
	height:35px;
 }
 .tech .describe{
	font-family: "Microsoft Yahei";
	margin-right: 12px;
	text-align: center;
 }
 .tech .progress {
  float:left;
  height: 25px;
  background: #f2f2f2;
  border-left: 1px solid transparent;
  border-right: 1px solid transparent;
  width:70%;
}
.tech .progress > span {
  position: relative;
  float: left;
  margin: 0 -1px;
  min-width: 30px;
  height: 25px;
  line-height: 21px;
  text-align: right;
  background: #cccccc;
  border: none;
  border-color: #bfbfbf #b3b3b3 #9e9e9e;
  -webkit-box-shadow: inset 0 1px rgba(255, 255, 255, 0.3), 0 1px 2px rgba(0, 0, 0, 0.2);
  box-shadow: inset 0 1px rgba(255, 255, 255, 0.3), 0 1px 2px rgba(0, 0, 0, 0.2);
}
.tech  .progress > span > span {
	padding: 0 8px;
	font-size: 14px;
	color: #404040;
	color: rgba(0, 0, 0, 0.7);
	font-family: "Microsoft Yahie";
	line-height: 25px;
}
.tech .progress > span:before {
  content: '';
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1;
  height: 25px;
  border-radius: 10px;
}
.tech .progress .green {
  background: #49C085;
}
.tech .progress .darkblue {
  background: #7782D1;
}
.tech .progress .red {
  background:  rgb(245, 138, 135);
}
.tech .progress .orange {
  background: #f2b63c;
}
.tech .progress .blue {
  background: #6F92FF;
}
@media (min-width: 750px) {
	.tech .describe{
		width:130px;
		float:left;
	}
	.tech .progress {
		width:79%;
		float:left;
	}
}
@media (max-width: 750px) {
	.tech .describe{
		width:100%;
		margin-bottom:5px;
		text-align:left;
	}
	.tech .progress {
		width:100%;
		margin-bottom:5px;
	}
}
</style>
