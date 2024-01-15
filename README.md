# Anticorp Wiki
    
## What?
We run a private Discord/ XMPP/ Matrix server wherein most of our members post #resources related to a lot of cool stuff. That shit was getting out of control, in order to give #resources some structure and for the sake of longevity, it was mutually decided to spin up a Wiki for the same.

## Contribution

### For members

- Clone the repository
```bash
$ git clone https://github.com/anticorpware/anticorp-wiki --recurse-submodules
```

- Install Hugo Extended version

For more information, check their official [documentation](https://gohugo.io/installation/)


- Adding new content

If you're not adding any content, just edit the files and follow the add-commit-push step afterwards

```bash
$ hugo new 'docs/Learning Resources/filename.md'
```

- Update `filename.md`

```
---
title: "Filename"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Filename

### Resources
- This is a sample resource: [Link](https://example.com)
- This is another resource: [Link](https://example.com)
```

- Add your shit to the staging area, commit the changes and push it
```
$ git add location/filename.md
$ git commit -S -m "Add a proper commit message"
$ git push -u origin main
```

### For non-members
Send a PR, most of the steps remain the same. It may get rejected as we generally accept PR from folks who 
are a member of our server but not of the GitHub organisation.

