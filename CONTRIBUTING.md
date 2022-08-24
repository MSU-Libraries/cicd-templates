# Contributing

Although these templates are used on GitLab's CI/CD. The GitLab instance
we (MSU Libraries) are using them on has restricted access to some of it's
features required for contribution including: issue creating, forking, and
merge requests. Because of that, we are making this repository also available
on GitHub for ease of access and will maintain the repository in both places.

## Ask questions or report issues

Please direct all questions to the
[GitHub discussion board](https://github.com/MSU-Libraries/cicd-templates/discussions)
and report issues or bugs via
[GitHub issues](https://github.com/MSU-Libraries/cicd-templates/issues).

## Submitting patches

**First time setup**  
Log into you GitHub account and then click the *Fork* button on the [repository home page](https://github.com/MSU-Libraries/cicd-templates).


Clone the repository locally and navigate into that directory:  
```
git clone https://github.com/MSU-Libraries/cicd-templates.git
cd cicd-templates
```

Now add your fork as a new remote:
```
git remote add fork https://github.com/{username}/cicd-templates
```

Create a new branch for your changes:
```
git checkout -b your-branch-name
```

**Start coding**  
Make sure you have the latest repository data:
```
git fetch origin
```

Create a new branch for your changes off of the main branch:
```
git checkout -b your-branch-name origin/main
```
As you are writing your templates, make sure you are following the
[GitLab template authoring guidelines](https://docs.gitlab.com/ee/development/cicd/templates.html#template-authoring-guidelines).

Commit changes as you go to your forked branch:
```
git push -set-upstream fork your-branch-name
```

**Submitting your changes**  
Once you have completed all of the above steps you are ready to submit your pull request. Please follow
the [official GitHub documentation for pull requests](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
But basically you can just go back to the [repository's home page](https://github.com/MSU-Libraries/cicd-templates) and click on
*Pull Request* and follow the prompts to submit it.
