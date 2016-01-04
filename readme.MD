
To create repo on Github and push local code onto repo, you can follow cmds as below:
```
curl -u 'muchcontact' https://api.github.com/user/repos -d '{"name":"reponame"}'
git remote add origin git@github.com:muchcontact/reponame.git
git push origin master
```




