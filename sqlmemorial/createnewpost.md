---
layout: page
title: Creating a New Memorial Post
permalink: /createnewpost/
---
# Creating a New Memorial Post

This page covers the general process for creating a new memorial page if someone from our community has passed. Please ensure that before you create a post that you have confirmation and an obituary or other information from the next of kin.

This post is based on the [basic jekyll instructions](https://jekyllrb.com/docs/posts/) for a new post.

## Create a New File
Each memorial post is a new blog post in the Jekyll system. Please use the date of death (as best determined) for the name of the file, along with the name of the person.

The format ought to be: YYYY-MM-DD-nameofperson.md

As an example, for Gareth Swanepoel, who passed on 8 Jan 2021, a post is created with the name: 2021-01-08-garethswanepoel.md

The file ought to be created in the /sqlmemorial/_posts folder.

## File Structure
The heading in the file ought to be include this data:
```
---
layout: post
title:  "In Memory of Gareth Swanepoel"
date:   2021-01-14 00:00:00 -0500
categories: memorial
---
```

The title should be changed to reflect the individual's name. The date/time should reflect the date/time of passing. For now, the category for these pages is the memorial.

### Official Obituary

Below this, the first heading should include the person's formal name and title, i.e. Mr. Gareth Swanepoel

### Thoughts and Memories

Under this heading, include an H2 heading with the text "Thoughts and Memories from Friends". The text under this section ought to be items submitted by individuals that knew the person.

## File Format
The file ought to be in markdown format. This will be converted to HTML by Jekyll during the build process. 

A [markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) can help you to format the text.

## Other Items
If there are other items to include, please alter this page and submit a PR to update the guidance for all future posts.