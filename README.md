# tripela-net.github.io

### Requirements:

- Hugo: https://gohugo.io/installation/
- Git: https://git-scm.com/downloads

### Tutorials:

#### Serve the website in localhost

You can run the website on [http://localhost:1313](http://localhost:1313/) with the following comand:`hugo serve -D`

#### Create new blogpost

Use the following content to generate new blogpost skeleton `hugo new content content/blog/<BLOGPOST_NAME>.md`

Open the `.md` file and edit. Remove the draft line and add `author = "Tripela Authors"` and add `description=<DESCRIPTION> field too.`

#### Git

1. Use `git add .` to add all changes
2. Commit: `git commit -m "<COMMIT_MESSAGE>"`
3. Push: `git push`
