<ol>
<li>На странице репозитория имеется кнопочка <strong>«Fork»,</strong> которую и следует нажать.</li>
<li>Клонируем репозиторий:<br><code>git clone https://github.com:Uncontrollablee/listWithIslom.git</code></li>
<li><code>cd listWithIslom</code></li>

<li>Связываем с оригинальным репозиторием: <br><code>git remote add upstream git://github.com/hack-1200/listWithIslom.git</code><br><code>git fetch upstream</code></li>
<li>Создаём новую ветвь, названную "feature" и делаем её активной:<br><code>git checkout -b feature</code></li>
<li>Как только вы сделали работу (или её часть), отправьте её в свою копию репозитория на GitHub:<br><code>git push origin feature </code>#Загружает изменения в текущей ветви в origin в ветвь feature</li>
<li>Коммитим: <br><code>git add .</code><br><code>git commit -m "Your commit"</code></li>
<li>Отправляем в GitHub: <br><code>git push</code></li>
<li><code> git pull original master</code></li>

</ol>
