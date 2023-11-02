<h1> How to Turn any GitHub Repo into a (Free) CDN </h1>
<h5><em> NOTE : &nbsp Make sure you have made your repo public </em></h5>

<h4> JSDeliver </h4>
<h5> Format : &nbsp https://cdn.jsdelivr.net/gh/:user/:repo@:version/:path-to-file.ext </h5>
<strong> Various usage example base on target release : </strong>
<br>
<li> https://cdn.jsdelivr.net/npm/jquery@latest/dist/jquery.min.js &nbsp --> always point to the latest version </li>
<li> https://cdn.jsdelivr.net/npm/jquery@3/dist/jquery.min.js &nbsp --> fixed major version </li>
<li> https://cdn.jsdelivr.net/npm/jquery@3.7/dist/jquery.min.js &nbsp --> fixed minor version </li>
<li> https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.min.js &nbsp --> fixed version </li>
<br><br>

<h4> Statically </h4>
<h5> Format : &nbsp https://cdn.statically.io/gh/:user/:repo/:branch/:path-to-file.ext </h5>
<p> These branches are cached for only 1 day: main, master, dev, develop, and gh-pages. </p>
<p> Otherwise, files will be cached on the CDN for 1 year. </p>
<br><br>

<h4> Raw.Githack </h4>
<strong> This service has 2 usage formats : </strong>
<br>
<li> https://raw.githack.com/gh/:user/:repo/:branch/:path-to-file.ext &nbsp --> instant changes but traffic will be throttled </li>
<li> https://raw.githack.com/gh/:user/repo/:commit-hash/:path-to-file.ext &nbsp --> files are cached permanently </li>
<br><br>

<em> to be continued </em>
