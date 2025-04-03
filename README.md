<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nike Shoes Website | Ludiflex</title>
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
    <link rel="stylesheet" href="sneak.css">
</head>
<body>
    <div class="body_items">
        
        <div class="item_2">
            <img src="https://i.ytimg.com/vi/O1C0ZMBCL_I/maxresdefault.jpg" alt="">
        </div>
        <div class="just_do_it">
            <p>Just
               Do
               It
            </p>
        </div>
    </div>    
    <div class="container">
        <nav>
            <div class="left_nav">
                <div class="nav_logo">
                    <img src="http://getwallpapers.com/wallpaper/full/9/2/c/713206-beautiful-cool-shoes-hd-wallpapers-1920x1200-for-android-tablet.jpg" alt="">
                </div>
                <div class="nav_menu">
                    <ul>
                        <nav class="bg-black bg-opacity-80 fixed w-full z-50"><div class="container mx-auto flex justify-between items-center py-4 px-6"><ul class="hidden md:flex space-x-8"><li style="opacity: 1; transform: none;"><a href="#home" class="text-white hover:text-gray-300 text-lg font-semibold transition-colors">Home</a></li><li style="opacity: 1; transform: none;"><a href="#services" class="text-white hover:text-gray-300 text-lg font-semibold transition-colors">Services</a></li><li style="opacity: 1; transform: none;"><a href="#about" class="text-white hover:text-gray-300 text-lg font-semibold transition-colors">About Us</a></li><li style="opacity: 1; transform: none;"><a href="#contact" class="text-white hover:text-gray-300 text-lg font-semibold transition-colors">Contact Us</a>
</li></ul></div></nav><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu h-8 w-8 text-white md:hidden"><line x1="4" x2="20" y1="12" y2="12"></line><line x1="4" x2="20" y1="6" y2="6"></line><line x1="4" x2="20" y1="18" y2="18"></line></svg>
                        
                        
                        
                        
                    </ul>
                </div>
            </div>
            
        </nav>
        <div class="main">
            <div class="left_col">
                <div class="shoe_title">
                    <p>sneakstarZ</p>
                </div>
                <div class="line">
                    <hr>
                </div>
                <div class="shoe_description">
                    <p>bring it down in torrents flood                          
    the mud suck my pink sneakers off
         this joyless path...</p>
                </div>
                

                
            </div>
            <div class="right_col">
                <img src="images/1.png" class="featured_img" alt="">
                <div class="shopping_cart_btn">
                    <i class="bx bx-cart"></i>
                </div>
            </div>
        </div>
    </div>
<script src="sneak.js"></script>
     
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
