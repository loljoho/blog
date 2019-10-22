---
layout: post
title:  "Title Here"
author: "My Name"
date:   2019-10-22 12:34:56 -0400
update: 
categories: dev
---

This is an example markdown post to show you how to contribute to this blog.

In order to do so, follow the directions as outlined below...


**1. Clone the repo:**
```bash
git clone https://github.com/loljoho/blog.git
```

**2. Enter the directory:**
```bash
cd blog/
```

**3. Checkout a new branch:**
```bash
git checkout -B post/title-here
```

**4. Copy this file to the `_posts/` dir:**
```bash
# make sure you rename the target filename properly!
#
# that includes the YYY-MM-DD bit
# as well as the title-of-your-post
# don't forget the .markdown extension
cp _drafts/2019-10-22-title-here.markdown _posts/2019-10-22-title-here.markdown
```

***5. Modify the [YAML Front Matter](https://jekyllrb.com/docs/front-matter/) accordingly:**
```ruby
layout: post
title:  "Title Here"
author: "My Name"
date:   YYY-MM-DD HH:MM:SS -0400
update: YYY-MM-DD HH:MM:SS -0400 # leave blank; only do if applicable!
categories: dev
```

**6. Make your changes, commmit, and push to `gh-pages` on `origin`:**
```bash
git add _posts/2019-10-22-title-here.markdown
git commit -m 'Create Post: Title Here'
git push origin post/title-here
```

**7. Make a Pull Request on GitHub and notify me**

 - Make a new **Pull Request** on GitHub
 - Make sure it's merging into `gh-pages`
 - Shoot me a message after you do so!

Voilà!

---

Fin.