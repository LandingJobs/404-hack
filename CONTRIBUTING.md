# Contributing

We love pull requests from everyone. By participating in this project, you're encouraged to submit [pull requests](https://github.com/LandingJobs/404-hack/pulls), [propose features and discuss issues](https://github.com/LandingJobs/404-hack/issues). When in doubt, ask a question using issues.

#### Fork the Project

Fork the [project on Github](https://github.com/LandingJobs/404-hack) and check out your copy.

```
git clone https://github.com/[your-name]/404-hack.git
cd 404-hack
git remote add upstream https://github.com/LandingJobs/404-hack.git
```

#### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your feature or bug fix.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```

#### Write Code

Implement your feature or bug fix.

#### Write Documentation

Document any external behavior in the [README](README.md).

#### Update Changelog

Add a line to [CHANGELOG](CHANGELOG.md) under *Next Release*. Make it look like example below, including your name and link to your Github account.

```
* [#123](https://github.com/LandingJobs/404-hack/pull/1): New Feature x - [@contributor](https://github.com/[your-name]).
```

#### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what changed and why.

```
git add ...
git commit
```

#### Push

```
git push origin my-feature-branch
```

#### Make a Pull Request

Go to https://github.com/[your-name]/404-hack and select your feature branch. Click the 'Pull Request' button and fill out the form. Pull requests are usually reviewed within a few days.

#### Rebase

If you've been working on a change for a while, rebase with upstream/master.

```
git fetch upstream
git rebase upstream/master
git push origin my-feature-branch -f
```

#### Update CHANGELOG Again

Update the [CHANGELOG](CHANGELOG.md) with the pull request number. A typical entry looks as follows.

```
* [#123](https://github.com/LandingJobs/404-hack/pull/1): New Feature x - [@contributor](https://github.com/[your-name]).
```

Amend your previous commit and force push the changes.

```
git commit --amend
git push origin my-feature-branch -f
```

#### Be Patient

It's likely that your change will not be merged and that the nitpicky maintainers will ask you to do more, or fix seemingly benign problems. Hang on there!

#### Thank You

Please do know that we really appreciate and value your time and work. We love you, really.

* Change [your-name] with your Github username.
