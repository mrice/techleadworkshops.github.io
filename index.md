---
layout: default
---

## Case-study based workshops to improve your team's tech leadership skills. Yours to run at your company or at your next Meetup!

### Welcome, (future) tech lead!

Becoming a great tech lead, senior software engineer, architect, principal engineer, whatever you want to call it, takes time and practice to develop all the skills they didn't tech you in computer sciene. 

They call them soft skills because they can't *really* be studied. Without practice, you're going to bumble through the role until situations come up to teach you the "soft" skills you need. **Let's short circuit that process and get some practice.**

### Get Some Practice; Be a Leader; Get Started
You can read about leadership and study it all you want, but you won't get real practice until real leadership moments come up. Leadership is like public speaking in that way.

These **tech lead workshops** are designed to give you and your team some practice before the situations come up.

Consider starting a weekly lunch group at your company or even a Meetup in your city!

### The Workshops

{% for post in site.categories["workshops"]  %}
  **[{{ post.title }}]({{ post.url }})** - {{post.excerpt  | remove: '<p>' | remove: '</p>'}}
{% endfor %}

### Get Involved
<!--TODO-->

Got an idea for a workshop you don't see? Give us a workshop idea (example) by sending Michael an email or cloning this site and contributing your own!

Start a group at your company or even a Meetup group in your city!

{% include sharing.html %}