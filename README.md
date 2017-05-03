# Website with goHugo & Wercker

`cd` to local folder:

```bash
git add .
git commit -m "commit message"
git push -u origin master
```

To regenerate the website’s HTML code when Wercker deployment is not used you will need to run Hugo and upload the public submodule to GitHu

```bash
hugo
cd public
git add .
git commit -m "Build message"
git push -u origin master
```

These links were pretty useful:
+ [georgecushen blog](https://georgecushen.com/create-your-website-with-hugo/#installing-hugo)
+ [goHugo](http://gohugo.io/tutorials/automated-deployments/)
+ [ryanwalls blog](https://3dsim.github.io/using-hugo-and-wercker-to-create-and-automate-your-own-site/)
