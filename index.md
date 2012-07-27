## Welcome

Hey… this is [DPP's](http://twitter.com/dpp) quick playground for [Telegram](https://telegr.am)
related stuff.

This site is [a public GitHub repository](https://github.com/dpp/plaything)
 so you can see the source and maybe
even play with the source by forking it.

## Movie test

<div>
	A movie should go here:
	<video width="320" height="240" controls id="video">
	  <source src="https://telegram-media.s3.amazonaws.com/initial_telegram_screencast.mov" type="video/mp4">
	  Woof!!
  </video>


<video controls id="video" width="512" height="384" preload autobuffer >
	  <source src="https://telegram-media.s3.amazonaws.com/initial_telegram_screencast.mov" type="video/mp4" >
            <!--RENDERED ON BROWSERS WITH NO HTML5 VIDEO SUPPORT-->
            <object id="flashcontent" width="512" height="384" type="application/x-shockwave-flash" data="/player.swf" style="visibility: visible;">
			<param name="bgcolor" value="#000000">
			<param name="allowscriptaccess" value="always">
			<param name="flashvars" value="videoPath=https://telegram-media.s3.amazonaws.com/initial_telegram_screencast.f4v&posterPath=/com/poster/myPosterFrame.jpg&skinPath=/com/skin/skin.swf">
			</object>
             <!---->
        </video>


</div>

## Blog Posts

Welcome to my blog.  Here are my most recent blog posts:


<ul class="posts" style="list-style: none" data-lift="blog.posts?max=15">
    <li data-post="item"><h2><a data-post="link" href="#">Blog Post</a></h2>
    	<h4 style="padding-left: 8px;"><span data-post="date">2012/12/14</span> </h4>
    	<div style="padding-left: 15px;" data-post="shortcontent">
			Post Content goes here
    </div>
	<div data-post="more"><a href="#">Read More...</a></div>
    <hr>
    </li>
</ul>


<div>
	<head_stuff>
	    

		<link href="https://vjs.zencdn.net/c/video-js.css" rel="stylesheet">
		<script src="https://vjs.zencdn.net/c/video.js"></script>


	
		<script type="text/javascript" src="/com/js/swfobject/swfobject.js"></script>		
		<script type="text/javascript">
			var flashvars = {};
			var params = {};

			params.bgcolor = "#000000";
			params.allowscriptaccess = "always";

			flashvars.videoPath = "https://telegram-media.s3.amazonaws.com/movie.f4v";
			flashvars.posterPath = "/com/poster/myPosterFrame.jpg";
			flashvars.skinPath = "/com/skin/skin.swf";

			var stageW = 512;
			var stageH = 384;

			var attributes = {};
			attributes.id = "flashcontent";			

			swfobject.embedSWF("/player.swf", "flashcontent", stageW, stageH, "9.0.0", false, flashvars, params, attributes);
		</script>
	</head_stuff>
</div>
[title: Home]: /