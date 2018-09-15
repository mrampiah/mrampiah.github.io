---
layout: page
title: Hi!
order: 1
icon: fa-location-arrow
skill-icons:
 - title: AWS
   class: aws
---

I'm a software engineer from [Ghana][ghana-facts] currently residing in Worcester, Massachusetts after completing my Bachelor's in Computer Science at Worcester Polytechnic Institute (WPI). I developed a passion for software development in middle-school, having witness my dad thrive in the same field. Shortly after picking up my first Visual Basic book I knew I wanted to turn this into a career. Since then, I've taught myself several languages using projects to ensure each concept is deeply rooted. A self-starter, I wrote applications for our school's dining hall and tuck shop, as well as lead a couple of high school mates to create our very first e-voting system. Each of these continue to be maintained as an ongoing class project for the generations that have followed.

I've always been a fast learner but WPI has taught me the skills to be even more proficient. Having to complete several different projects requiring a variety of technologies, I've mastered the art of moving from a total novice to advanced user in a matter of days; a direct result of completing full courses in 7-week terms.

I'm very interested in the arts and have used my technical knowledge to support this passion, recording movies and music on a number of occasions. I've also played the lead in a drama production and sang solo and duets all in front of a large public audience. These experiences have helped increase my confidence far beyond any academic accolades, being previously insecure about them.

Now to the main reason for this page - to potential future employers, I have my resume along with a recommendation from one of my professors in the following sections. Also check out projects I've completed including links to code in the [Portfolio][portfolio] section. Thanks!

# Skills
{% for icon in skill-icons %}
  <a class="skill-icon--link {{ icon.class }}" href="{{ icon.url }}">
    {% include {{ icon.class | prepend: 'skill-icons/' | append: '.svg' }} %}
    <span class="skill-icon--title visuallyHidden">{{ icon.title }}</span>
  </a>
{% endfor %}

[ghana-facts]: https://www.gvi.co.uk/blog/16-interesting-facts-about-ghana/ 'Some Facts about the Motherland'

[fun-zone]:/the-fun-zone.html

[portfolio]:/portfolio.html