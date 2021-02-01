# Like Ruby? Dislike Installing Things On Your Computer?

Do you like Ruby? Great! Do you dislike installing language runtimes? Do you like worrying about language versions? Clashing language versions? Between apps?

If you like Ruby and hate the rest, this is the lab for you! Actually, if you hate all of the above you may still find this lab useful!

### Why Ruby?

Dude, I like Ruby. It's just a means-to-an-end :P

### Docker? What's That?

_or why not use a VM?_

For the sake of simplicity, it felt conceptually easier to just tell someone:
1. hey you. YEAH YOU. Go [HERE](https://www.docker.com/products/docker-desktop)
2. ok. install that bro.
3. ok cool, you're ready for this lab. :D

### But...WHY?

Most languages these days have an official Docker container somewhere. Instead of installing everything required for the language to run on **ONE** machine, why not package it up in a runnable sandbox that can be transported between machines? While leveraging official Docker containers?

# So in order continue with this lab you need Docker :D

## Step 1: Docker Crash Course

As mentioned above, most languages have a Docker image/registry that's officially supported. Ruby is no exception. [Here's their registry](https://hub.docker.com/_/ruby?tab=tags&page=1&ordering=last_updated&name=3.0.0)

Let's get started! Create the following `Dockerfile` at the top level of this repository and open a Pull-Request. Since we're super cool, let's just get started with Ruby 3:

```Dockerfile
FROM ruby:3.0.0-alpine3.13
```

You can also choose from any of the other tags on that page.

<hr>
<h3 align="center">Watch below this comment for my response</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
