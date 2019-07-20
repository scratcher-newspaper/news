# How-To 記事の書き方
```sh
git checkout master
(記事を書く)
git add .
git commit -m "記事"
git push origin master
cd ..
python compiler.py pages
cd pages
git checkout gh-pages
git add .
git commit -m "記事HTML版"
git push origin gh-pages
```
