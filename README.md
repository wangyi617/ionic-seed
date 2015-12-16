This seed project will auto concat and uglify the js files in <code>www/js/</code> to <code>www/dist/dist_js/</code>, change the html files in <code>www/templates/</code> to <code>www/js/templates.js</code>, and simplify the packaging file.
# Guide
1. Set your app's name
 in _ionic.project_, _package.json_ and _config_xml_, change the "ionic-seed" to your app name, change the id "com.anasit.ionic-seed" to your id
2. Add platform
<code>$ ionic platform add android</code> or <code>$ ionic platform add ios</code>
3. Install dependencies
<code>$ npm install</code>
<code>$ ionic state restore --plugins</code>
4. Run app
<code>$ ionic serve</code> or <code>$ ionic build android</code>
