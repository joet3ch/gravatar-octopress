#gravatar-octopress

Plugin to display your Gravatar avatar in the sidebar of your Octopress site.

##Howto:

- Copy 'gravatar.html' to the '_includes/custom/asides' directory.

- Generate your Gravatar hash (md5 of your email address)

> example:
> $ md5 -s joe@t3ch.com
> MD5 ("joe@t3ch.com") = 0380746aa5a0a708ed6b09324be42cb3

- Add your gravatar hash to the '_config.yml' file using the example provided.

- Add 'gravatar.html' to your default_asides variable in '_config.yml'

> example:
> default_asides: [custom/asides/gravatar.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]