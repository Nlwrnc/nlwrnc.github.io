---
name: Halo Wars 2
tools: [Game]
image: https://upload.wikimedia.org/wikipedia/en/f/f6/Hw2_coverart.png
description: After spending decades in cryogenic sleep, the crew of the Spirit of Fire wake to find themselves on a Forerunner installation known as the Ark. But they are not alone.
year: 2017
company: Creative Assembly
role: Technical Animator
tasks: ["Rigging and skinning assets", "Implementing assets into engine", "Creating tools to support the animation team"]
---

# Halo Wars 2
{% include elements/tags.html tags=page.tools year=page.year%}

{% include elements/video.html link="https://www.youtube.com/embed/6RHzU9r0t2c?si=fv5qMQCPqJfO8tuU" %}

<div class="row justify-content-left align-items-left">
    <div class="col-md-6">
        {% include projects/project_company_card.html company=page.company role=page.role %}
        {% include projects/project_tasks.html tasks=page.tasks %}
    </div>
    <div class="col-md-6">
        {% include elements/text_card.html text=page.description %}
    </div>
</div>
