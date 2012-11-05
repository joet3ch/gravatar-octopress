#gravatar-octopress

Plugin to display your Gravatar avatar in the sidebar of your Octopress site.

Live example at <a href="http://joet3ch.com">http://joet3ch.com</a>


##Howto:

- Copy 'gravatar.html' to the '_includes/custom/asides' directory.

- Generate your Gravatar hash (md5 of your email address)

**Mac OS**
> $ md5 -s joe@t3ch.com

> MD5 ("joe@t3ch.com") = 0380746aa5a0a708ed6b09324be42cb3

**Linux**
> $ echo joe@t3ch.com | md5sum -
> 5cf9c07033d63892d325c62a6eca6975  -


- Add your gravatar hash to the '_config.yml' file using the example provided.

- Add 'gravatar.html' to your default_asides variable in '_config.yml'

> default_asides: [custom/asides/gravatar.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]