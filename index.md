# Ben's Website

# My Interests
Robotics

# My Blog
I'm on a journey to capture achievements and current struggles in robotics journey
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }} </a>
        </li>
    {% endfor %}
</ul>

# Get in Touch
<ul>
<li> <a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
<li> <a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>

# My Repositories
<ul>
<li> <a href="https://benbdon.github.io/HelloWorld/">Hello World Project </a></li>
</ul>