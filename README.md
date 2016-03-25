<h1>Website Performance Optimization</h1>  
<h2>Following techniques used:</h2>  
<ul>
    <li>Images are compressed</li>
    <li>Add async tag to js source to avoid render blocking</li>
    <li>Use <a href ="https://github.com/typekit/webfontloader">Web Font Loader</a> to load fonts</li>
    <li>Inline CSS used to optimize CSS delivery</a></li>
    <ul>Two issues are fixed in views/js/main.js
        <li>line 455, remove redudant dom searching but keep the variable for using in loop</li>
        <li>line 508, remove redudant dom searching and keep the scroll variable out of loop and reuse it in loop</li>
    </ul>
</ul>

<h2>Test:</h2>
<p>Use <a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insights</a> to test following pages</p>