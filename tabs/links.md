---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Links"
    info: "Links to my other places."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Professional"
      type: id_professional
      color: "gray"
    - title: "Game Development"
      type: id_gamedev
      color: "#F4A273"
    - title: "Project Links"
      type: id_projects
      color: "#62b462"

  list:
    # Professional
    - type: id_professional
      title: "Linkedin"
      url: "https://www.linkedin.com/in/ryan-feller-b66783220/"
      info: "My Linkedin page, which contains info about myself and recent happenings in my professional life."
    - type: id_professional
      title: "Resume Download"
      url: "https://drive.google.com/uc?export=download&id=1TsAbYsuPfoq8cWErlbV40pbTRDfJRB6F"
      info: "A link to download my resume directly."
      -
    # Project Links
    - type: id_projects
      title: "Wikipedia X (Twitter) Bot"
      url: "https://x.com/random_wiki__"
      info: "An automated X (Twitter) account that posts a high-quality random Wikipedia article every hour."
      -
    # Game Development
    - type: id_gamedev
      title: "Heroes' Emporium"
      url: "https://momke72.itch.io/heroesemporium"
      info: "A potion mixing game made in 2 days for GMTK 2023!"
    - type: id_gamedev
      title: "Meowchelmy"
      url: "https://momke72.itch.io/meowchelmy"
      info: "A hitman-style stealth game about a cat sneaking around a fortress."
    - type: id_gamedev
      title: "Little Dice"
      url: "https://victorghys.itch.io/little-dice"
      info: "A platformer-puzzle game made in 2 days for GMTK 2022!"
    - type: id_gamedev
      title: "Beat Brawl"
      url: "https://momke72.itch.io/beat-brawl"
      info: "A rhythm game made in an afternoon"
    - type: id_gamedev
      title: "Sublime Monkey Perfection"
      url: "https://momke72.itch.io/monkey-kong"
      info: "A fast-paced platformer made for my school's programming club"
    - type: id_gamedev
      title: "RunnerOS"
      url: "https://abhorrentpropaganda.itch.io/runneros"
      info: "A desktop-themed platformer made in 2 days for GMTK 2021. Placed in the top 1%!"
    - type: id_gamedev
      title: "Idol's Tower"
      url: "https://momke72.itch.io/idolstower"
      info: "A top-down dungeon crawler game made in a week for BLACKTHORNPOD Game Jam #3!"
    - type: id_gamedev
      title: "Cryptologist"
      url: "https://momke72.itch.io/cryptologist"
      info: "A code-breaking game made in an afternoon for the Historically Accurate Game Jam 3."
    - type: id_gamedev
      title: "Panda in Space"
      url: "https://momke72.itch.io/panda-in-space"
      info: "A rage-platforming game made for the Beginner's Circle Jam #3."
    - type: id_gamedev
      title: "Chit Chat"
      url: "https://momke72.itch.io/chit-chat"
      info: "A game about communication, made for the 'Game By it's Cover Jam."
    - type: id_gamedev
      title: "Ichor"
      url: "https://momke72.itch.io/ichor"
      info: "A greek themed 3D arena-shooter game."
      
      
      
---
