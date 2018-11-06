
<div class="git-empty">
<fieldset data-spm-anchor-id="0.0.0.i0.51202399hxoRNg">
<h5>Git 全局设置</h5>
<pre class="light-well">git config --global user.name "neal.qu"
git config --global user.email "hanxinid@163.com"
</pre>
</fieldset>
<fieldset>
<h5>创建新版本库</h5>
<pre class="light-well">git clone <span class="clone">git@github.com:qushaoye2009/doc.git</span>
cd doc
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
</pre>
</fieldset>
<fieldset>
<h5>已存在的文件夹或 Git 仓库</h5>
<pre class="light-well">cd existing_folder
git init
git remote add origin <span class="clone">git@github.com:qushaoye2009/doc.git</span>
git add .
git commit
git push -u origin master
</pre>
</fieldset>
</div>
