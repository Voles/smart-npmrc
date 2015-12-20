> If you use the --save flag to auto-update package.json, npm installs the packages with a leading carat (^), putting your modules at risk of drifting to different versions. This is fine for module development, but not good for apps, where you want to keep consistent dependencies between all your environments.

Via the [Heroku blog](https://blog.heroku.com/archives/2015/11/10/node-habits-2016)

