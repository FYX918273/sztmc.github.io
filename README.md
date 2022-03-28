<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<title>疯子</title>
</head>
<link href="file:///F|/TDDOWNLOAD/网站特效/69/69/css/niutuku.css" type="text/css" rel="stylesheet">
<body>
<script type="text/javascript" src="file:///F|/TDDOWNLOAD/网站特效/69/69/js/niutuku.js"></script>
<div id="idContainer" class="container">
  <div id="idContent" class="content">
    <table cellpadding="0" cellspacing="0">
      <tr align="center">
        <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634195637644598882.html"><img src="file:///F|/TDDOWNLOAD/网站特效/69/69/images/tx-img05.jpg" /></a>1. 首页</div></td>
        <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634198169567772500.html"><img src="images/txyj.jpg" width="359" height="270" /></a>2. 天下一家</div></td>
         <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634176761535371250.html"><img src="images/mkf.jpg" width="130" height="75" /></a>3. 麦克风之家</div></td>
        <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634177396830602491.html"><img src="images/jlxx.jpg" width="120" height="75" /></a>4. 交流学习</div></td>
        <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634176761967715000.html"><img src="file:///F|/TDDOWNLOAD/网站特效/69/69/images/js03.jpg" /></a>5. 资源下载</div></td>
        <td><div><a href="http://www.niutuku.com/hihilinxuan/log/634177399939528638.html"><img src="images/kxyk.jpg" width="959" height="366" /></a>6. 开心一刻</div></td>
      </tr>
    </table>
  </div>
  <div class="slider_left" id="idSliderLeft"></div>
  <div class="slider" id="idSlider">
    <div class="bar" id="idBar">
      <div class="bar_left"></div>
      <div class="bar_right"></div>
    </div>
  </div>
  <div class="slider_right" id="idSliderRight"></div>
</div>
<script>
var sld = new Slider("idSlider", "idBar", {
    MaxValue: $("idContent").scrollWidth - $("idContent").clientWidth,
    onMin: function(){ $("idSliderLeft").style.backgroundPosition = "bottom left"; },
    onMax: function(){ $("idSliderRight").style.backgroundPosition = "bottom right"; },
    onMid: function(){ $("idSliderLeft").style.backgroundPosition = "top left"; $("idSliderRight").style.backgroundPosition = "top right"; },
    onMove: function(){ $("idContent").scrollLeft = this.GetValue(); }
});
sld.SetPercent(.5);
sld.Ease = true;
$("idSliderLeft").onmouseover = function(){ sld.Run(false); }
$("idSliderLeft").onmouseout = function(){ sld.Stop(); }
$("idSliderRight").onmouseover = function(){ sld.Run(true); }
$("idSliderRight").onmouseout = function(){ sld.Stop(); }
</script>
<div style="width:98%;margin:20px auto; padding:50px 0; clear:both; overflow:hidden;">
<p><strong><a href="http://www.xdlm.com" target="_blank">兄弟联盟欢饮您</a></strong> </p>
<p></p>
<p>转载请自觉注明出处！注：此代码仅供学习交流，请勿用于商业用途。</p>
</div>
</body>
</html>
