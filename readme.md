```ruby
find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

touch .gitignore
echo .DS_Store >> .gitignore

git add .gitignore
git commit -m '.DS_Store banished!'
```

Reading:

https://novemberfall.github.io/Java-ObjectOriented/


