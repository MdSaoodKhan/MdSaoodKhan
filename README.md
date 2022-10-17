### Hi there 👋
### I'm Saood.


[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=MdSaoodKhan)](https://github.com/anuraghazra/github-readme-stats)
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
Showing icons
To enable icons, you can pass show_icons=true in the query param, like so:

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
Themes
With inbuilt themes, you can customize the look of the card without doing any manual customization.

Use &theme=THEME_NAME parameter like so :

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
All inbuilt themes
Github readme stats comes with several built-in themes (e.g. dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula).

GitHub Readme Stats Themes

You can look at a preview for all available themes or checkout the theme config file & you can also contribute new themes if you like :D

Customization
You can customize the appearance of your Stats Card or Repo Card however you wish with URL parameters.

Common Options
title_color - Card's title color (hex color). Default: 2f80ed.
text_color - Body text color (hex color). Default: 434d58.
icon_color - Icons color if available (hex color). Default: 4c71f2.
border_color - Card's border color (hex color). Default: e4e2e2 (Does not apply when hide_border is enabled).
bg_color - Card's background color (hex color) or a gradient in the form of angle,start,end. Default: fffefe
hide_border - Hides the card's border (boolean). Default: false
theme - name of the theme, choose from all available themes. Default: default theme.
cache_seconds - set the cache header manually (min: 7200, max: 86400). Default: 14400 seconds (4 hours).
locale - set the language in the card (e.g. cn, de, es, etc.). Default: en.
border_radius - Corner rounding on the card. Default: 4.5.
Warning We use caching to decrease the load on our servers (see #1471 (comment)). Our cards have a default cache of 4 hours (14400 seconds). Also, note that the cache is clamped to a minimum of 4 hours and a maximum of 24 hours.

Gradient in bg_color
You can provide multiple comma-separated values in the bg_color option to render a gradient with the following format:

&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
Stats Card Exclusive Options
hide - Hides the specified items from stats (Comma-separated values). Default: [] (blank array).
hide_title - (boolean). Default: false.
card_width - Set the card's width manually (number). Default: 500px (approx.).
hide_rank - (boolean) hides the rank and automatically resizes the card width. Default: false.
show_icons - (boolean). Default: false.
include_all_commits - Count total commits instead of just the current year commits (boolean). Default: false.
count_private - Count private commits (boolean). Default: false.
line_height - Sets the line height between text (number). Default: 25.
exclude_repo - Exclude stars from specified repositories (Comma-separated values). Default: [] (blank array).
custom_title - Sets a custom title for the card. Default: <username> Github Stats.
text_bold - Use bold text (boolean). Default: true.
disable_animations - Disables all animations in the card (boolean). Default: false.
Note When hide_rank=true, the minimum card width is 270 px + the title length and padding.

Repo Card Exclusive Options
show_owner - Show the repo's owner name (boolean). Default: false.
Language Card Exclusive Options
hide - Hide the languages specified from the card (Comma-separated values). Default: [] (blank array).
hide_title - (boolean). Default: false.
layout - Switch between two available layouts default & compact. Default: default.
card_width - Set the card's width manually (number). Default 300.
langs_count - Show more languages on the card, between 1-10 (number). Default 5.
exclude_repo - Exclude specified repositories (Comma-separated values). Default: [] (blank array).
custom_title - Sets a custom title for the card (string). Default Most Used Languages.
Warning Language names should be URI-escaped, as specified in Percent Encoding (i.e: c++ should become c%2B%2B, jupyter notebook should become jupyter%20notebook, etc.) You can use urlencoder.org to help you do this automatically.

Wakatime Card Exclusive Options
hide - Hide the languages specified from the card (Comma-separated values). Default: [] (blank array).
hide_title - (boolean). Default false.
line_height - Sets the line height between text (number). Default 25.
hide_progress - Hides the progress bar and percentage (boolean). Default false.
custom_title - Sets a custom title for the card (string). Default Wakatime Stats.
layout - Switch between two available layouts default & compact. Default default.
langs_count - Limit the number of languages on the card, defaults to all reported languages (number).
api_domain - Set a custom API domain for the card, e.g. to use services like Hakatime or Wakapi (string). Default Waka API.
range – Request a range different from your WakaTime default, e.g. last_7_days. See WakaTime API docs for a list of available options. (YYYY-MM, last_7_days, last_30_days, last_6_months, last_year, or all_time). Default all_time.
GitHub Extra Pins
GitHub extra pins allow you to pin more than six repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

Usage
Copy-paste this code into your readme and change the links.

Endpoint: api/pin?username=anuraghazra&repo=github-readme-stats

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
Demo
Readme Card

Use show_owner variable to include the repo's owner username

Readme Card

Top Languages Card
The top languages card shows a GitHub user's most frequently used top language.

Note Top Languages does not indicate my skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. It is a new feature of github-readme-stats._

Usage
Copy-paste this code into your readme and change the links.

Endpoint: api/top-langs?username=anuraghazra

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
Exclude individual repositories
You can use the &exclude_repo=repo1,repo2 parameter to exclude individual repositories.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
Hide individual languages
You can use &hide=language1,language2 parameter to hide individual languages.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
Show more languages
You can use the &langs_count= option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
Compact Language Card Layout
You can use the &layout=compact option to change the card design.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
Demo
Top Langs

Compact layout
Top Langs

Wakatime Week Stats
Change the ?username= value to your Wakatime username.

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
Note: Please be aware that we currently only show data from Wakatime profiles that are public.

Demo
willianrod's wakatime stats

willianrod's wakatime stats

Compact layout
willianrod's wakatime stats

All Demos
Default
Anurag's GitHub stats

Hiding specific stats
Anurag's GitHub stats

Showing icons
Anurag's GitHub stats

Customize Border Color
Anurag's GitHub stats

Include All Commits
Anurag's GitHub stats

Themes
Choose from any of the default themes

Anurag's GitHub stats

Gradient
Anurag's GitHub stats

Customizing stats card
Anurag's GitHub stats

Setting card locale
Anurag's GitHub stats

Customizing repo card
Customized Card

Top languages
Top Langs

WakaTime card
willianrod's wakatime stats

Quick Tip (Align The Repo Cards)
By default, GitHub does not lay out the cards side by side. To do that, you can use this approach:

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
Deploy on your own Vercel instance
Check Out Step By Step Video Tutorial By @codeSTACKr
Warning If you are on the hobby (i.e. free) Vercel plan, please make sure you change the maxDuration parameter in the vercel.json file from 30 to 10 (see #1416 for more information).

Since the GitHub API only allows 5k requests per hour, my https://github-readme-stats.vercel.app/api could possibly hit the rate limiter. If you host it on your own Vercel server, then you do not have to worry about anything. Click on the deploy button to get started!

Note Since #58, we should be able to handle more than 5k requests and have fewer issues with downtime 😁.

Deploy to Vercel

🛠️ Step-by-step guide on setting up your own Vercel instance
Keep your fork up to date
You can keep your fork, and thus your private Vercel instance up to date with the upstream using GitHubs' Sync Fork button. You can also use the pull package created by @wei to automate this process.

💖 Support the project
I open-source almost everything I can and try to reply to everyone needing help using these projects. Obviously, this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are a few ways you can do it:

Giving proper credit when you use github-readme-stats on your readme, linking back to it :D
Starring and sharing the project 🚀
paypal.me/anuraghazra - You can make one-time donations via PayPal. I'll probably buy a coffee tea. 🍵
Thanks! ❤️

https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss

Contributions are welcome! <3

Made with ❤️ and JavaScript.




<!--
**MdSaoodKhan/MdSaoodKhan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


[![@mdsaoodkhan's Holopin board](https://holopin.io/api/user/board?user=mdsaoodkhan)](https://holopin.io/@mdsaoodkhan)
