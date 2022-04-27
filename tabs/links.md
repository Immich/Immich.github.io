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
# check the meta_common_description in _data/lang/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
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
    header: "Talks and Workshops"
    info: "Talks, workshops and podcasts in which I've participated"

  # To change order of the Categories, simply change order. (you don't need to change list order.)8C52FF #8459DB
  category:
    - title: "Machine Learning"
      type: id_ml
      color: "#00C2CB"
    - title: "Algorithmic Fairness"
      type: id_fairness
      color: "#F4A273"
    - title: "Software Engineering"
      type: id_swe
      color: "#62b462"
    - title: "Natural Language Processing"
      type: id_nlp
      color: "#FF66C4"

  list:
    -
    # ML
    - type: id_ml
      title: "How to get started in a Data role (ESP)"
      url: "https://youtu.be/lAfXWNwfDdw"
      info: >
        10/2021 <br> Talk for the NASA Space Apps Challenge about how to get started in Data, diferent data roles, and the skills required to be sucessful in this field.

    - type: id_ml
      title: "Panel Women In AI (EN)"
      url: "https://www.youtube.com/watch?v=jAhceV6KbWg"
      info: >
        08/2020 <br> Panelist in <a href="https://www.riiaa.org/" target="_blank">RIIAA</a> to discuss Machine Learning, Ethics and Diversity in AI.

    - type: id_ml
      title: "AI + Healthcare (ESP)"
      url: "https://www.youtube.com/watch?v=VR2UTbZnF4I"
      info: >
        07/2018 <br> This talk introduces to AI algorithms applied in Healthcare. It was also discussed how Artificial Intelligence, instead of replacing doctors, can extend their capabilities.

    - type: id_ml
      title: "Intro to Artificial Intelligence (ESP)"
      url: 
      info: >
        07/2017 <br> An introductory talk for <a href="https://www.laboratoria.la/" target="_blank">Laboratoria</a> students.


    # SWE
    - type: id_swe
      title: "Panel: The Complexity of Software Development"
      url: "https://docker.events.cube365.net/dockercon/2022"
      info: >
        05/2022 <br> Panelist at the dockercon

    # Fairness and Ethics    
    - type: id_fairness
      title: "AI Ethics: How to Ensure Fairness in the Algorithms we create"
      url: 
      info: >
        10/2021<br> International Guest Speaker in the master course of "Data Science" (with reference 7CS034) at the School of Mathematics and Computer Science of the Faculty of Science and Engineering of the University of Wolverhampton in the United Kingdom.

    - type: id_fairness
      title: "AI Ethics: How to Ensure Fairness in the Algorithms we create"
      url:
      info: >
        09/2020<br> International Guest Speaker in the master course of "Data Science" (with reference 7CS034) at the School of Mathematics and Computer Science of the Faculty of Science and Engineering of the University of Wolverhampton in the United Kingdom.

    - type: id_fairness
      title: "Biases in the AI design process (ESP)"
      url: "https://open.spotify.com/episode/54puJoAWoWJryfJtbBztgI?si=219ac6bb29904e34"
      info: >
        07/2020 <br> Part I. Podcast about how AI biases and how to design with an ethical perspective."

    - type: id_fairness
      title: "Biases in the AI design process (ESP)"
      url: "https://open.spotify.com/episode/0MdKK9kT2HoxrNo9YWiEWI?si=f58b126c05054f30"
      info: >
        07/2020 <br> Part II. Podcast about how AI biases and how to design with an ethical perspective.

    - type: id_jekyiiliquid
      title: "Liquid for Programmers"
      url: "https://github.com/Shopify/liquid/wiki/Liquid-for-Programmers"
      info: "Liquid for Programmers wiki on GitHub"
    - type: id_jekyiiliquid
      title: "Liquid Reference"
      url: "https://shopify.dev/api/liquid/"
      info: "Liquid is a template language created by Shopify and written in Ruby. It is now available as an open source project on GitHub"

    # webdesign
    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many more."
  
    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many more."

    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many more."


    # NLP
    - type: id_nlp
      title: "Natural Language Processing Techniques: NER - Named Entity Recognition (ESP)"
      url: "https://youtu.be/Z9Bkha3u00g"
      info: >
        04/2018 <br> This talk is about Information Extraction Systems and Named Entity Recognition, a very known technique in NLP.

    - type: id_nlp
      title: "Natural Language Processing Models (ESP)"
      url: "https://www.youtube.com/watch?v=kNC8V7MjKp8"
      info: >
        02/2018 <br> This talk introduces how Natural Processing Models are related to different processes in the brain, and how machines are able to process and understand the language we (humans) use in our in our daily life. It also introduces different NLP techniques, and the level of implementation and difficulty of each. Finally, an NLP example is provided and an outline of what you need to know and learn to apply NLP is discussed.
---
