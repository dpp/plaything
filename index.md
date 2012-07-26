## Welcome

Hey… this is [DPP's](http://twitter.com/dpp) quick playground for [Telegram](https://telegr.am)
related stuff.

This site is [a public GitHub repository](https://github.com/dpp/plaything)
 so you can see the source and maybe
even play with the source by forking it.

## Movie test

<div>
	A movie should go here:
	<div id="flashcontent">
		<p>This ScreenFlow video requires a more recent version of the Adobe Flash Player to display.  Please update your version of the <a href="http://www.adobe.com/go/getflashplayer">Adobe Flash Player</a>.</p>
	</div>	
	
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


<head_stuff>
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

[title: Home]: /