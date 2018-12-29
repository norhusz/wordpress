1. Start Compression – Gzip and DEFLATE

	Enabling Gzip Compression in WordPress via .htaccess reduces Server Response Time
	and volume of data sent by the server to web browser. Certainly, compressed page size
	help reducing the transferred response and data. The best way to enable compression is,
	using mod_gzip or mod_deflate in WordPress .htaccess file.
	And the good news is, Gzip compression can be enabled by adding
	a simple code in WordPress .htaccess file of your website.

	
2. Enable Keep Alive

	Enable Keep Alive – Speed up WordPress using Htaccess
	Enabling Keep Alive is another powerful Htaccess trick to speed up WordPress website.
	It enables your server and web browser to download resources on a single connection,
	hence it increases page speed.
	You can enable Keep Alive by adding ‘Connection: Keep-	Alive’ HTTP header in your server.
	Keep Alive comes auto-enabled on most of the modern Apache servers.
	However, you can manually enable Keep Alive on old Apache Servers.
	
3. Leverage Browser Caching

	Enable Browser Caching – Leverage Browser Caching via Htaccess
	
	Leverage Browser Caching via Htaccess is one of the most recommended Htaccess
	tricks to speed up WordPress website by the developers.
	Most of all optimization tools like GTmatrix and Google PageSpeed Insights
	recommends to Enable Browser Caching. Browser Caching enabled websites told
	web browsers to store/keep website resources like JS or CSS files for a specified period.
	So that, web browsers do not need to download the same resources again.
	As a result, the website loads faster because the browser uses the already downloaded resources.
	
	You can Enable Leverage Browser Caching in WordPress by:
	
	1. Adding Expires Headers
	2. Adding Cache-Control Headers and
	3. Turning ETags Off
	
4. Disable Image Hotlinking
5. Activate mod_pagespeed
