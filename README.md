# Blog

> Was gonna name the repository "Bloggy-McBlogface" but that'd be like, super annoying

Anyways, I created this blog when I noticed *many* students were struggling with particular issues, and there didn't seem to be any good examples/tutorials/articles out there that laid it all out in simple, easy-to-understand (and less technical) terms.

I genuinely hope it brings as much elation, entertainment, and education to its readers as much as it did for me while I was developing it!


---


## Details

This is a simple blog built with [Jekyll][jekyll-site], a static site generator in [Ruby][ruby-site], and deployed on [GitHub Pages][gh-pages].  It relies on [Markdown][markdown-wiki] for its posts, and functions without any database!

I've created partial lists of the technologies and techniques I employ in the development of this project.


### Technologies

 - [VSCode][vscode-site] editor
 - [Ruby][ruby-site] v2.6.5 via [rvm][rvm-site]
 - [RubyGems][rubygems-site] package manager
   - [Jekyll v3.8.6][jekyll-3.8.6-repo]
   - [Bundler][bundler-site]
   - [Minima][minima-repo] theme
   - [GitHub Pages][gh-pages-gem]
 - [Sass/Scss][sass-site] preprocessor language for stylesheets
 - [Icomoon][icomoon-site] icon font & SVG generator


### Development & Workflow

 - I use `gh-pages` instead of `master` because I'm deploying directly to a GitHub Pages project site
 - I (obviously) use my GitHub repository to manage my development process
 - I adhere to [Semantic Versioning][semver], although it is not as much of a priority or concern given the nature of this project.
 - More on this later!


---


## Usage


### Requirements

 - [Ruby][ruby-site] v2.6.5 or above
 - [RubyGems][rubygems-site]
 - [Jekyll][jekyll-3.8.6-repo] v3.8.6 (*not* 4.0.0 or above!)
 - [Bundler](https://jekyllrb.com/docs/ruby-101/#bundler)
 - ...and all the [Jekyll requirements](https://jekyllrb.com/docs/installation/)
 - Wait, are you seriously considering cloning this and running it?


### Procedure

Clone the repository and enter the directory:
```bash
git clone https://github.com/loljoho/blog.git
cd blog/
```

Install the project gems:
```bash
bundle install
```

Congratulations, you've made it this far!  Serve it up:
```bash
bundle exec jekyll serve
```

Now you just need to browse to http://localhost:4000/blog/ to see it.




---


## Contributing

### Contributing Posts

If you wish to contribute a post to the blog, I will write a detailed thingy to outline it.  

Make sure you change the `author` value in the YAML front matter of your file accordingly.


### Contributing Code

Please, for the love of Buddha, if you have some serious CSS/Sass/Scss skills and a good eye for design, reach out to me!

If you only have a good eye for design, reach out to me!

If you suck at design, then I don't know.


---


## Miscellaneous

Fin.




[ruby-site]:https://www.ruby-lang.org/en/
[jekyll-site]:https://jekyllrb.com/
[gh-pages]:https://pages.github.com/
[markdown-wiki]:https://en.wikipedia.org/wiki/Markdown

[vscode-site]:https://code.visualstudio.com/
[rvm-site]:https://rvm.io/
[jekyll-3.8.6-repo]:https://github.com/jekyll/jekyll/tree/v3.8.6
[bundler-site]:https://bundler.io/
[rubygems-site]:https://rubygems.org/
[gh-pages-gem]:https://github.com/github/pages-gem
[minima-repo]:https://github.com/jekyll/minima
[sass-site]:https://sass-lang.com/
[icomoon-site]:https://icomoon.io

[git-workflow]:https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
[git-branching]:https://nvie.com/posts/a-successful-git-branching-model/
[repo-issues]:https://github.com/loljoho/blog/issues
[repo-milestones]:https://github.com/loljoho/blog/milestones
[repo-projects]:https://github.com/loljoho/blog/projects
[gh-help-projects]:https://help.github.com/en/articles/about-project-boards
[semver]:https://semver.org/
