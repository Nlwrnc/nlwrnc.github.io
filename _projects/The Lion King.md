---
name: The Lion king
tools: [Film]
image: https://upload.wikimedia.org/wikipedia/en/9/9d/Disney_The_Lion_King_2019.jpg
description: Simba, a young lion prince, flees his kingdom after the murder of his father, Mufasa. Years later, a chance encounter with Nala, a lioness, causes him to return and take back what is rightfully his.
year: 2019
company: MPC
role: Animation Discipline Developer
tasks: ["Assisting and supporting the animation team", "Maintaining and developing animation tools", "Developing tools for the virtual production pipeline", "Automating the caching of environment geometry for large and complex scenes", "Developed a tool for managing viewport presets in Maya"]
---

# The Lion King
{% include elements/tags.html tags=page.tools year=page.year%}

{% include elements/video.html link="https://www.youtube.com/embed/7TavVZMewpY?si=lTPavTDcOgDYUcNO" %}

<div class="row justify-content-left align-items-left">
    <div class="col-md-6">
        {% include projects/project_company_card.html company=page.company role=page.role %}
        {% include projects/project_tasks.html tasks=page.tasks %}
    </div>
    <div class="col-md-6">
        {% include elements/text_card.html text=page.description %}
    </div>
</div>
