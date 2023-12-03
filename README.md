<h1 align="left">
    Simulation Engineer &mdash; Data Enthusiast
</h1>

<div id="projects">
    {% assign sortedProject = site.projects | sort: 'order' %}
    {% for project in sortedProject %}
        <hr>
        <p>
            <strong>{{ project.title }}</strong> &mdash;
            {{ project.languages }}<br>
            {{ project.excerpt }}
        </p>
    {% endfor %}
</div>
