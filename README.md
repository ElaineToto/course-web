<html><head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
     <title>HTML5 SVG沙漠日出动画场景特效</title>
    
    
    <meta name="Keywords" content="HTML5 SVG沙漠日出动画场景特效">
    
    
    <meta name="description" content="HTML5 SVG沙漠日出动画场景特效">
    
    <link href="http://img.chinaz.com/max-templates/passport/styles/topbar.css" type="text/css" rel="Stylesheet">
    <link href="/style/style_kj.css" type="text/css" rel="stylesheet">
    <link href="/style/demo.css" type="text/css" rel="stylesheet">
    <script type="text/javascript" src="/style/js/jquery-1.2.pack.js"></script>
<script type="text/javascript">
var theme_list_open = false;
$(document).ready(function () {
	function fixHeight() {
		var headerHeight = $("#switcher").height();
		$("#iframe").attr("height", $(window).height()-84 + "px");
	}
	$(window).resize(function () {
		fixHeight();
	}).resize();
	//响应式预览
	$('.icon-monitor').addClass('active');
	$(".icon-mobile-3").click(function () {
		$("#by").css("overflow-y", "auto");
		$('#iframe-wrap').removeClass().addClass('mobile-width-3');
		$('.icon-tablet,.icon-mobile-1,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
		$(this).addClass('active');
		return false;
	});

	$(".icon-mobile-2").click(function () {
		$("#by").css("overflow-y", "auto");
		$('#iframe-wrap').removeClass().addClass('mobile-width-2');
		$('.icon-tablet,.icon-mobile-1,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
		$(this).addClass('active');
		return false;
	});

	$(".icon-mobile-1").click(function () {
		$("#by").css("overflow-y", "auto");
		$('#iframe-wrap').removeClass().addClass('mobile-width');
		$('.icon-tablet,.icon-mobile,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
		$(this).addClass('active');
		return false;
	});

	$(".icon-tablet").click(function () {
		$("#by").css("overflow-y", "auto");
		$('#iframe-wrap').removeClass().addClass('tablet-width');
		$('.icon-tablet,.icon-mobile-1,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
		$(this).addClass('active');
		return false;
	});

	$(".icon-monitor").click(function () {
		$("#by").css("overflow-y", "hidden");
		$('#iframe-wrap').removeClass().addClass('full-width');
		$('.icon-tablet,.icon-mobile-1,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
		$(this).addClass('active');
		return false;
	});
});
</script>
<script type="text/javascript">
function Responsive($a) {
	if ($a == true) $("#Device").css("opacity", "100");
	if ($a == false) $("#Device").css("opacity", "0");
	$('#iframe-wrap').removeClass().addClass('full-width');
	$('.icon-tablet,.icon-mobile-1,.icon-monitor,.icon-mobile-2,.icon-mobile-3').removeClass('active');
	$(this).addClass('active');
	return false;
};
</script>
</head>
<body id="by" style="overflow-y: hidden">
<div id="switcher">
  <div class="center">
    <ul>
    <li class="logoTop">在线预览！</li>
      <div id="Device">
        <li class="device-monitor"><a href="javascript:"><div class="icon-monitor active"></div></a></li>
        <li class="device-mobile"><a href="javascript:"><div class="icon-tablet"> </div></a></li>
        <li class="device-mobile"><a href="javascript:"><div class="icon-mobile-1"> </div></a></li>
        <li class="device-mobile-2"><a href="javascript:"><div class="icon-mobile-2"> </div></a></li>
        <li class="device-mobile-3"><a href="javascript:"><div class="icon-mobile-3"> </div></a></li>
      </div>
      
      
    </ul>
    <div class="muen_top">
     <a href="/" class="indexactive">首页</a>
     <a href="/tupian/" class="l11active" target="_blank">高清图片</a>
     <a href="/moban/" class="l12active" target="_blank">模板</a>
     <a href="/ppt/" class="l726active" target="_blank">ppt模板</a>
     <a href="/tubiao/" class="l49active" target="_blank">图标</a>
     <a href="/kuzhan/" class="l713active" target="_blank">酷站</a>
     <a href="http://font.chinaz.com/" class="l13active" target="_blank">字体</a>
     <a href="/psd/" class="l713active" target="_blank">PSD素材</a>
     <a href="/shiliang/" class="l15active" target="_blank">矢量图</a>
     <a href="/yinxiao/" class="l713active" target="_blank">音效</a>
     <a href="/biaoqing/" class="l560active" target="_blank">表情</a>
     <a href="http://desk.chinaz.com/" class="l713active" target="_blank">壁纸</a>
     <a href="/donghua/" class="l653active" target="_blank">动画</a>
     <a href="/jiaoben/" target="_blank">脚本</a>
     <a href="/zhuanti/" target="_blank">专题</a>
    </div>
    <div class="tougao">
    <a href="http://sc.chinaz.com/tougao.html" target="_blank">我要投稿</a>
    </div>
  </div>
</div>
<div id="iframe-wrap">

		    <iframe id="iframe" src="http://demo.sc.chinaz.com//Files/DownLoad/webjs1/201811/jiaoben6349" frameborder="0" width="100%" height="573px"> </iframe>
          


</div>
<div id="footer-notice" class="kj_bottom">
	<div style=" width:980px; margin:0 auto">
		<p class="left cut">
			<span>名称：</span>
            <a href="/jiaoben/181113561890.htm" title="点击下载" class="down" target="_blank">HTML5 SVG沙漠日出动画场景特效</a>
			<span>类型：</span>
			<a href="/jiaoben/" class="colbule" title="脚本" target="_blank">脚本</a>
             
			<span>标签：</span><a href="/tag_jiaoben/HTML5.html" target="_blank">HTML5</a><a href="/tag_jiaoben/SVG.html" target="_blank">SVG</a><a href="/tag_jiaoben/ShaMo.html" target="_blank">沙漠</a><a href="/tag_jiaoben/DongHuaChangJing.html" target="_blank">动画场景</a>
                        

		</p>
		<p class="left">
			<span>分享到：</span>
			<a title="分享到新浪微博" href="javascript:void(0)" id="fxwb" class="sn">新浪</a>
			<a title="分享到腾讯微博" href="javascript:void(0)" onclick="posttoWb()" class="tx">腾讯</a>
			<a title="分享到QQ空间" href="javascript:window.open('http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?url='+encodeURIComponent(document.location.href));void(0)" class="qq">QQ空间</a>
		</p>
		<div class="clear"></div>
	</div>
</div>

	<script type="text/javascript">

	    var description = 'HTML5 SVG沙漠日出动画场景特效: HTML5 SVG沙漠日出动画场景特效是一款基于svg绘制金字塔沙漠里日落日出动画场景特效。';



	    var sendT = {
	        getHeader: function () {
	            var g_title = description;
	            var re = /<[^<>]*?font[^<>]*?>/gi;
	            g_title = g_title.replace(re, "");
	            return g_title;
	        },
	        getFirstImgSrc: function () {
	            var allPageTags = document.getElementsByTagName("div");
	            for (var i = 0; i < allPageTags.length; i++) {
	                if (allPageTags[i].className == 'downtext') {
	                    if (allPageTags[i].getElementsByTagName("img")[0] && allPageTags[i].getElementsByTagName("img")[0].width > 200) {
	                        return allPageTags[i].getElementsByTagName("img")[0].src;
	                    }
	                    else {
	                        return null;
	                    }

	                }
	            }
	        },
	        getContent: function () {
	            var allPageTagss = document.getElementsByTagName("div");
	            for (var i = 0; i < allPageTagss.length; i++) {
	                if (allPageTagss[i].className == 'downtext') {
	                    return allPageTagss[i].innerHTML;
	                }
	            }
	        }
	    }



	    document.getElementById("fxwb").onclick = function () {
	        (function (s, d, e, r, l, p, t, z, c) {
	            var f = 'http://service.weibo.com/share/share.php?appkey=872996044&', u = z || d.location, p = ['url=', e(u), '&title=', e(sendT.getHeader()), '&source=', e(r), '&sourceUrl=', e(l), '&content=', c || 'gb2312', '&pic=', e(p || '')].join('');
	            function a() {
	                if (!window.open([f, p].join(''), 'mb', ['toolbar=0,status=0,resizable=1,width=440,height=430,left=', (s.width - 440) / 2, ',top=', (s.height - 430) / 2].join(''))) u.href = [f, p].join('');
	            };
	            if (/Firefox/.test(navigator.userAgent)) setTimeout(a, 0); else a();
	        })(screen, document, encodeURIComponent, 'CHINAZ', 'http://sc.chinaz.com/', sendT.getFirstImgSrc(), null, null, null);
	    }


	    function posttoWb() {
	        var _tt = description;
	        var _t = encodeURI(_tt.replace(/\s+$/, ''));
	        var _url = encodeURI(window.location);
	        var _appkey = encodeURI("258efff116d2466da9b7513cbae7de0b");
	        var _site = encodeURI('sc.chinaz.com');
	        var _pic = sendT.getFirstImgSrc();
	        var _u = 'http://v.t.qq.com/share/share.php?title=' + _t + '&url=' + _url + '&appkey=' + _appkey + '&site=' + _site + '&pic=' + _pic;
	        window.open(_u, '转播到腾讯微博', 'width=700, height=580, top=320, left=180, toolbar=no, menubar=no, scrollbars=no, location=yes, resizable=no, status=no');
	    }

 
</script>
<script type="text/javascript" src="/js/softinfo.js.aspx?id=632578" defer="defer" charset="UTF-8"></script>
<div style="display:none">
<script src="http://s4.cnzz.com/stat.php?id=300636&amp;web_id=300636" language="JavaScript"></script><script src="http://c.cnzz.com/core.php?web_id=300636&amp;t=z" charset="utf-8" type="text/javascript"></script><a href="https://www.cnzz.com/stat/website.php?web_id=300636" target="_blank" title="站长统计">站长统计</a>
</div>


</body></html>
