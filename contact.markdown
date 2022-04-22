---
layout: page
title: 联系方式
permalink: /contact/
---

![about](/static/about/about2.jpg "About EASTOM")

## 联系方式

* 地址： 东莞市虎门镇龙眼九路53号
* 电话： 0769-81227490 82887982
* 传真： 0769-81227704
* 邮箱： ba7lnn@dgeastom.com
* 网址： http://www.dgeastom.com
* 联系人： 彭生 ：137 25860 789


## 导航地图

<!--地图开始-->
<script type="text/javascript" src="http://api.map.baidu.com/api?v=2.0&ak=OfldXkI591GW281wpaUBSHES"></script>
<style type="text/css">
#allmap {width: 100%;height: 400px;margin-top:20px;overflow: hidden;font-family:"微软雅黑";}
#allmap b{color: #CC5522;font-size: 14px; }
#allmap img{max-width: none;}
</style>
<div id="allmap"></div>
<script type="text/javascript">
	  var map = new BMap.Map("allmap");
	  map.centerAndZoom(new BMap.Point(113.707371,22.845636), 18);
	  var marker1 = new BMap.Marker(new BMap.Point(113.707371,22.845636));  // 创建标注
	  map.addOverlay(marker1);              // 将标注添加到地图中
	  //marker1.setAnimation(BMAP_ANIMATION_BOUNCE); //跳动的动画				
	  //创建信息窗口 
	  var infoWindow1 = new BMap.InfoWindow("<b>东莞市羿通实业有限公司</b><br>地址：东莞市虎门镇龙眼九路53号<br>电话：0769-81227490");
	  marker1.openInfoWindow(infoWindow1);
	  //marker1.addEventListener("click", function(){this.openInfoWindow(infoWindow1);});	
	  //向地图中添加缩放控件
 var ctrl_nav = new BMap.NavigationControl({anchor:BMAP_ANCHOR_TOP_LEFT,type:BMAP_NAVIGATION_CONTROL_LARGE});
 map.addControl(ctrl_nav);
      //向地图中添加缩略图控件
 var ctrl_ove = new BMap.OverviewMapControl({anchor:BMAP_ANCHOR_BOTTOM_RIGHT,isOpen:1});
 map.addControl(ctrl_ove);
      //向地图中添加比例尺控件
 var ctrl_sca = new BMap.ScaleControl({anchor:BMAP_ANCHOR_BOTTOM_LEFT});
 map.addControl(ctrl_sca);
 
 map.enableDragging();//启用地图拖拽事件，默认启用(可不写)
        map.enableScrollWheelZoom();//启用地图滚轮放大缩小
        map.enableDoubleClickZoom();//启用鼠标双击放大，默认启用(可不写)
        map.enableKeyboard();//启用键盘上下左右键移动地				
</script>
<!--地图结束-->