# Contributor Resources
Helpful information and resources for volunteer contributors to the WP Training Team

## How-to Screencasts

### Fork a Repo (Repository)

https://cl.ly/07380s0z3r16

## GitHub Standard Fork & Pull Request Workflow

https://gist.github.com/Chaser324/ce0505fbed06b947d962

### Edit a Lesson Plan

https://youtu.be/-QnjJIFlQyU

### Submit an Issue

https://screencast-o-matic.com/watch/cFejIGDoth

## Images in Lesson Plans
We prefer to have the image files stored in GitHub rather than linked from other locations on the web. Place them in the `/images/` folder and link to them using this relative URL:

```
> [Image description](/images/filename.png)
```

## Slides in Lesson Plans
Add the following to the lesson plan's Materials Needed section and change the "repo-name" part of the URL to the repo name for that lesson plan. This link will not work until the pull request for the lesson plan has been merged into the wptrainingteam's `dev` branch.

```
> [Slides](https://rawgit.com/wptrainingteam/repo-name/dev/slides/index.html) (included in this repo)
```

## Icons in Lesson Plans
The Make site had the ability to add alert boxes to lesson plans. We have lost that in the move to GitHub. However, we have chosen to use icons as a replacement.

The alert boxes in Make, which when migrated appear as shortcodes, should be converted as follows:
* [info] 		  ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/info.png)
* [tip]       ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png)
* [alert] 	  ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/flag.png)
* [warning] 	![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/dismiss.png)

To use these icons in Markdown for any lesson plan here on GitHub, copy and paste these links (including the blockquote marker) into the lesson plans:
```
> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/info.png)
> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png)
> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/flag.png)
> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/dismiss.png)
```
