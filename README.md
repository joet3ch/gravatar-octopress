#Introduction

Plugin to display your Gravatar avatar in the sidebar of your Octopress site.

Live example at <a href="http://www.joet3ch.com">http://www.joet3ch.com</a> and <a href="http://www.rayfaddis.com">http://www.rayfaddis.com</a>


##Installation:

1. Copy 'gravatar.html' to your '_includes/custom/asides' directory.
2. Copy 'gravatar.rb' to your 'plugins' directory.
3. Update your '_config.yml' file to include a 'gravatar_email' variable. Example below which is also in the provided _config.yml file:

        # Gravatar  
        gravatar_email: youraddress@example.com

4. Add 'gravatar.html' to your default_asides variable in the '_config.yml' settings file. Example:

        default_asides: [custom/asides/gravatar.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]