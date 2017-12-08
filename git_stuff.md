
##### Book of Git (Heroku version):octocat:

Writing down all my expiriences with git here. 

###### Forcefully pushing git repo to Heroku

Sometimes when working with Heroku and mangaging multiple apps on it, it can be difficult to keep
of everything. Especially for a young dev like me, who's got no expirience in managing intricate projects.

Sometimes, you may get a message saying that it's rejected, so in that case use

        git push heroku master -f
        
The -f argument ignores the warning and forcefully pushes your project to heroku.

        



