# LiMe-Lab-Cornell.github.io

## Cornell LINGUISTIC MEANING LAB Website

### Prerequisite

- The website is built using [jekyll] (https://jekyllrb.com/).
- Install Jekyll [Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/).
- If you cannot run Jekyll, check [GETTING STARTED] (https://jekyllrb.com/docs/) section.

### Local development

- Clone the repo from GitHub.
- Make some changes.
- View the change locally, run `bundle exec jekyll serve` from the root directory. The local server address will appear on the terminal, usually at `http://127.0.0.1:4000/`.

### Deployment

- `git status` view changes
- `git add .` add changes.
- `git commit -m "your comment"` add comment and commit.
- `git push` push changes to repo.

### JSON file

- To make title italic, use `<i> title </i>`
- To bold title , use `<b> title </b>`

* The collapse buttons use the Bootstrap button. This is a hard coding method, and change is welcomed. I continue using this way, then add the new publication, please change all the 7 to 8. If adding one more publication, 8 => 9.

```
"group": "myGroup7",
"groupId": "#myGroup7",
"ahref": "#Abstract7",
"aria-controls1": "Abstract7",
"data-bs-target": "#BibTeX7",
"aria-controls2": "BibTeX7"

```

```
"group": "myGroup8",
"groupId": "#myGroup8",
"ahref": "#Abstract8",
"aria-controls1": "Abstract8",
"data-bs-target": "#BibTeX8",
"aria-controls2": "BibTeX8"

```

- For the special character, JSON can read ASCII code or the rendered ASCII code. For example, `&#214;` = Ö, you could type either `&#214;` or Ö in JSON file.
