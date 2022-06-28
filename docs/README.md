# Docsify Project Docs

> This is a one-stop collection of all the documentation for my current [Hibbitts Design](https://hibbittsdesign.org/) open education and publishing [Docsify](https://docsify.js.org/#/) projects, delivered by - you guessed it - the magical documentation site generator Docsify.

## All the Docs

* [Docsify Open Course Starter Kit](https://hibbitts-design.github.io/docsify-project-docs/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/#/)
* [Docsify Open MultiCourse Starter Kit](https://hibbitts-design.github.io/docsify-project-docs/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-multicourse-starter-kit/main/#/)
* [Docsify Open Publishing Starter Kit](https://hibbitts-design.github.io/docsify-project-docs/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/#/)

## Technical Details

This is a customized [Docsify Open Publishing Starter Kit](https://github.com/hibbitts-design/docsify-open-publishing-starter-kit) site which can render multiple remote Markdown files (for example, a Markdown file in a GitHub repository).  

For example, to render a Markdown file named **README.md** (the expected default name) as a regular Docsify page the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/

To render a Markdown file named **README.md** (the expected default name) as a standalone page the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/&standalone=true

To render a Markdown file named **README.md** (the expected default name) as a standalone page with a table of contents the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/&standalone=true&toc=true

To render a Markdown file with a name other than README.md, for example **introduction.md** as a regular Docsify page, the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md

To render a Markdown file with a name other than README.md, for example **introduction.md** as a standalone page, the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&standalone=true

To render a Markdown file with a name other than README.md, for example **introduction.md** as a standalone page with a table of contents, the URL would be:  
https://hibbitts-design.github.io/docsify-open-publishing-starter-kit-remote/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&standalone=true&toc=true

_TIP: To get the path of a file on GitHub for the **basepath** URL parameter, tap the **Raw** button when viewing the file and then remove the filename. If not a README file, the filename will need to be passed using the **homepage** URL parameter._

---

**🙇🏻‍♂️Credits**  
[Beau Shaw](https://github.com/DaddyWarbucks) for his [Remote Docsify](https://github.com/DaddyWarbucks/remote-docsify) example.  
[Alan Levine](https://github.com/cogdog) for the inspiration of a consolidated ReadMe collection.
