# 🎓 awesome-teachcode

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🎓 Resources to use in the classroom, when writing tutorials, lesson plans/learning objectives, and when grading code-based assignments.

<!-- omit in toc -->
## Table of Contents {docsify-ignore}

- [Community](#community)
- [Course Tracking](#course-tracking)
- [Deployment](#deployment)
- [Diagramming](#diagramming)
- [Feedback](#feedback)
- [Code Reviews](#code-reviews)
- [Learning Objectives](#learning-objectives)
- [Presentations](#presentations)
- [Recording](#recording)

## Community

* **[dev.to](https://dev.to)**: Where programmers share ideas and help each other grow. An online community for sharing and discovering great ideas, having debates, and making friends. Anyone can share articles, questions, discussions, etc. as long as they have the rights to the words they are sharing. Cross-posting from your own blog is welcome.

## Course Tracking

Use [shields.io](https://shields.io) to embed automated code quality checks and other metrics in course tracking spreadsheets.

### How to Embed

Sample code assumes a column named `C2` contains a string in `username/reponame` format. Links to the associated GitHub repo.

**Example**: `droxey/tocsify`. ![droxey's last commit](https://img.shields.io/github/last-commit/droxey/tocsify.svg?style=flat)

```bash
=IF(C2 > 0, HYPERLINK(CONCATENATE("https://github.com/", C2), IMAGE(CONCAT(CONCAT("https://img.shields.io/github/last-commit/", C2), ".svg?style=flat"), 3), "")
```

## Deployment

* **[Glitch](https://glitch.com)**: Glitch is the friendly community where everyone can discover and create the best stuff on the web.
* **[Heroku](https://www.heroku.com)**: Fully-managed platform; the simplest path to delivering apps quickly.
* **[Netlify](https://www.netlify.com)**: An all-in-one workflow that combines global deployment, continuous integration, and automatic HTTPS.
* **[$100/60 Days @ DigitalOcean](https://try.digitalocean.com/performance/?refcode=a8556eabbc8a)**: Use this promo code to get $100 worth of credit over 60 days at [Digital Ocean](https://www.digitalocean.com).

## Diagramming

* **[sketchboard.io](sketchboard.io)**: Sketch software architectures, flow diagrams, mind maps, and more. Can share with the public and embed in lesson plans.

## Feedback

* **[Poll Everywhere](https://www.polleverywhere.com)**: Engage your class in real-time. Poll Everywhere transforms one-sided presentations into two-way conversations with an audience. This web-based audience response system lets you embed interactive activities directly into your presentation. The audience responds on the web or via SMS texting on their phones.

## Code Reviews

* **[reviewable.io](https://reviewable.io/)**: GitHub code reviews done right.
* **[CodeStream](https://github.com/TeamCodeStream/CodeStream)**: CodeStream is the knowledge base behind your codebase. Your dev team's discussions about code happen right inside the IDE, and are saved permanently with the code blocks to which they refer. That way your team, including its future members, benefits from working with an annotated codebase. With each discussion, your knowledge base grows and your codebase gets smarter over time.
* **[gitinspector](https://github.com/ejwa/gitinspector)**: Statistical analysis tool for git repositories. The default analysis shows general statistics per author, which can be complemented with a timeline analysis that shows the workload and activity of each author. Under normal operation, it filters the results to only show statistics about a number of given extensions and by default only includes source files in the statistical analysis.
* **[degit](https://github.com/Rich-Harris/degit)**: Makes copies of git repositories. Run `degit some-user/some-repo`, and degit will find the latest commit on https://github.com/some-user/some-repo and download the associated tar file to `~/.degit/some-user/some-repo/commithash.tar.gz` if it doesn't already exist locally.

## Learning Objectives

* **[List of Measurable Verbs](https://www.clinton.edu/curriculumcommittee/listofmeasurableverbs.cxml)**: A list of measurable verbs to assist you in writing course objectives and assess learning outcomes.
* **[Objectives Builder](http://teachonline.asu.edu/objectives-builder/)**: Use the ASU Online Objectives Builder tool to write measurable course outcomes and learning objectives.

## Presentations

* **[reveal.js](https://github.com/hakimel/reveal.js)**: Framework for easily creating beautiful presentations using HTML. Features include nested slides, Markdown contents, PDF export, speaker notes and a JavaScript API. Use in conjunction with [GitHub Pages](https://pages.github.com) for public, sharable, and open source presentations.
* **[reveal-md](https://github.com/webpro/reveal-md)**: [reveal.js](https://github.com/hakimel/reveal.js) on steroids! Get beautiful reveal.js presentations from Markdown files.

## Recording

* **[asciinema](https://asciinema.org)**: A free and open source solution for recording terminal sessions and sharing them on the web.
