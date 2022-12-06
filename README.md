# Geaux Brand Strategy Site 

This site was created with an [Eleventy starter made for a simple agile development workflow](https://github.com/11ty/eleventy-agile-blog) and was used to create a website for my Section 4 Brand Strategy Sprint through Section 4.

## Description

My goal is to create a website for every business sprint that I do in Section 4. I know I was busy when I initially did them, but I am going to go back through and create websites for all of them and update them to reflect courses I may or may not have finished.

I hate that I had such a shitty year for such a great slate of courses. Maybe I'll get to poke through them before the end of the year or I'll be able to afford th subscription next year. This is why somebody should hire me - so I can learn more and teach others what I know.

## Live Website

* [Geaux Brand Strategy](https://geauxbrandstrategy.netlify.app/)

## Getting Started

```
git clone https://github.com/GeauxWeisbeck4/geaux-brand-strategy-site.git my-blog-name
cd my-blog-name # Update `.eleventy.js` with your details
npm install
npm start
```
# Now more from the original template to learn about Agile...

## How the agile development workflow works

Use blog posts to describe your work, what you did, what you are about to do, then create "stories" that you add to the "backlog". Assign stories to "sprints", these last 1 week. Flesh out the stories, implement them, and then move these to "done" when you complete them. 

At the end of the week do a retrospective of what you did, and plan (i.e. create and assign stories to the next sprint) for the upcomming week.

Whenever you are a bit unsure of your path, read the above 2 paragraphs. You probably need to write a blog post.

The blog has the following pages:

- Home - Shows the past 3 blog posts and some useful links
- Archive - Shows all your blog posts
- Sprints - Shows all your sprints
- Backlog - Shows all your uncompleted stories
- Done - Shows all your completed stories
- About Me - A place to add contact details and personal info

Read the workflow description from the [week34 retrospective](https://festive-haibt-b7ead0.netlify.app/stories/retrospective-week34/) to get a better idea of how I am using the blog.

## Notes

- Sprints in /sprints must use the same file name pattern
- Add tag 'backlog' to a story to add it to the backlog page
- Add tag 'done' to a story to add it to the done page
- Regulary check in your changes to git
  - Create a week branch (e.g. week34)
  - Create story branches from your week branch
  - Merge story branches into the week branch
  - Merge week branches back into master
- Read up on [how eleventy works](https://www.11ty.dev/docs) so you can customise the blog
- You might want to add some git aliases to your shell to streamline working with git commands

Hopefully my description makes some sense, let me know how I could improve these docs.
