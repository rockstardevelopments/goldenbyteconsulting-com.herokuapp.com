README.markdown
==

Bootstrap
--
[Twitter Bootstrap](http://twitter.github.com/bootstrap/scaffolding.html#fluidGridSystem)

Pow
--
cd ~/.pow
ln -s /Users/martincrockett/Sites/goldenbyteconsulting-com.herokuapp.com goldenbyteconsulting-com
cd -
mkdir tmp
touch tmp/restart.txt

http://goldenbyteconsulting-com.dev

Git
--
git remote -v
git remote rm origin
git remote add origin git@github.com:rockstardevelopments/goldenbyteconsulting-com.herokuapp.com.git
git remote add heroku git@heroku.com:goldenbyteconsulting-com.git
git push -u origin master

git status
git add .
git commit -a -m "New page"
git commit -a -m "Updated page"
git push origin master
git push heroku master

Less
--
http://twitter.github.com/bootstrap/less.html#compiling

Google Analytics
--
<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-XXXXX-X']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>