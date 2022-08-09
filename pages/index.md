---
layout: page
permalink: /
---

{% include landing.html %}

# **About Me**

Hi, I am **{{ site.author.name }}** :wave:
<ul>
    <li>:globe_with_meridians: Computer Engineer focused in Web Development</li>
    <li>:man_technologist: Javascript developer in more than one flavor</li>
    <li>:book: Continuous Learner</li>
    <li>:busts_in_silhouette: Collaborator and Leader</li>
</ul> 

# **Career**
{% include about/timeline.html %}


# **Stack**

<div class="row">
{% include about/skills.html title="Major" source=site.data.major-programming-skills %}
{% include about/skills.html title="Casual" source=site.data.other-programming-skills %}
</div>

**Note:** *% = % of time in my **12 years** career*