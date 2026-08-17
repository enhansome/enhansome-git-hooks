# Awesome Git Hooks with stars

> A curated list of awesome [Git hooks](https://git-scm.com/docs/githooks)

Git Hooks are scripts that run automatically every time a particular event occurs in a Git repository.

## Contents

* [Useful Git Hooks scripts](#useful-git-hooks-scripts)
* [Tools](#tools)
* [Projects](#projects)
* [Articles](#articles)
* [Video Tutorials](#video-tutorials)
* [Support](#support)

## Useful Git Hooks scripts

* [pre-commit](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-commit) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - This hook is called before obtaining the proposed commit message.
* [prepare-commit-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/prepare-commit-msg) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Called after receiving the default commit message, just prior to firing up the commit message editor.
* [pre-receive](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-receive) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - This is called on the remote repo just before updating the pushed refs.
* [commit-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/commit-msg) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Can be used to adjust the message after it has been edited in order to ensure conformity to a standard or to reject based on any criteria.
* [pre-push](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-push) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Called prior to a push to a remote. In addition to the parameters, additional information, separated by a space is passed in through stdin in the form of `<local ref> <local sha1> <remote ref> <remote sha1>`.
* [pre-auto-gc](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-auto-gc) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Is used to do some checks before automatically cleaning repos.
* [pre-rebase](https://github.com/aitemr/awesome-git-hooks/tree/master/pre-rebase) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Called when rebasing a branch. Mainly used to halt the rebase if it is not desirable.
* [applypatch-msg](https://github.com/aitemr/awesome-git-hooks/tree/master/applypatch-msg) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Can edit the commit message file and is often used to verify or actively format a patch's message to a project's standards.
* [post-receive](https://github.com/aitemr/awesome-git-hooks/tree/master/post-receive) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - This is run on the remote when pushing after the all refs have been updated. It does not take parameters, but receives info through stdin in the form of `<old-value> <new-value> <ref-name>`.
* [post-rewrite](https://github.com/aitemr/awesome-git-hooks/tree/master/post-rewrite) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - This is called when git commands are rewriting already committed data.
* [post-commit](https://github.com/aitemr/awesome-git-hooks/tree/master/post-commit) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19 - Called after a successful commit. Useful for triggering notifications, etc.

## Tools

* [Husky](https://github.com/typicode/husky) ⭐ 35,275 | 🐛 108 | 🌐 JavaScript | 📅 2026-03-19 - Git hooks made easy.
* [pre-commit](https://github.com/pre-commit/pre-commit) ⭐ 15,506 | 🐛 26 | 🌐 Python | 📅 2026-08-10 - A framework for managing and maintaining multi-language pre-commit hooks.
* [Lefthook](https://github.com/Arkweid/lefthook) ⭐ 8,655 | 🐛 91 | 🌐 Go | 📅 2026-08-03 - Fast and powerful Git hooks manager for any type of projects.
* [overcommit](https://github.com/brigade/overcommit/) ⭐ 4,007 | 🐛 33 | 🌐 Ruby | 📅 2026-08-12 - A fully configurable and extendable Git hook manager.
* [Komondor](https://github.com/orta/Komondor) ⭐ 559 | 🐛 23 | 🌐 Swift | 📅 2023-03-02 - Git Hooks for Swift projects.
* [Githooks](https://github.com/rycus86/githooks) ⭐ 401 | 🐛 16 | 🌐 Shell | 📅 2025-08-26 - Auto-install Git hook, that supports hooks in any language checked into Git and also shared repos.
* [Grunt GitHooks](https://github.com/wecodemore/grunt-githooks) ⭐ 315 | 🐛 13 | 🌐 JavaScript | 📅 2022-08-03 - Setup, manage and update your hooks with Grunt. Can be used with all languages, supports templates.
* [Autohook](https://github.com/nkantar/Autohook) ⭐ 140 | 🐛 4 | 🌐 Shell | 📅 2025-07-01 - A very, very small Git hook manager with focus on automation.
* [Quickhook](https://github.com/dirk/quickhook/) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2026-07-28 - Faster Git hook (pre-commit, etc.) runner.
* [GitHooksVS](https://github.com/mstranne/GitHooksVS) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-07-09 - A Visual Studio extension for managing Git hooks.
* [Hooks](https://www.npmjs.com/package/node-hooks) - A command line git hook management tool.

## Projects

* [Lolcommits](https://github.com/mroth/lolcommits) ⭐ 4,816 | 🐛 40 | 🌐 Ruby | 📅 2026-08-10 - Takes a snapshot with your webcam every time you git commit code, and archives a lolcat style image with it.
* [Podmena](https://github.com/bmwant/podmena) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2022-03-07 - Enhance your commit messages adding random emoji to it.
* [GitPHPHooks](https://github.com/wecodemore/GitPHPHooks) ⭐ 64 | 🐛 1 | 🌐 PHP | 📅 2016-04-05 - Write your hooks in PHP, manage and organize them on a task and project level. Has an additional Hooks library on GitHub.
* [Commit Colors](https://github.com/sparkbox/commit-colors) ⭐ 44 | 🐛 2 | 🌐 Go | 📅 2022-11-13 - See a color swatch in your terminal every time you author a commit.
* [Git::Hooks](https://github.com/gnustavo/Git-Hooks) ⭐ 42 | 🐛 11 | 🌐 Perl | 📅 2024-06-16 - A framework for implementing Git (and Gerrit) hooks.
* [git-hooks-php](https://github.com/BernardoSilva/git-hooks-php) ⭐ 25 | 🐛 0 | 🌐 Shell | 📅 2018-04-23 - Git hooks for PHP based projects.
* [commandbox-githooks](https://github.com/elpete/commandbox-githooks) ⭐ 9 | 🐛 1 | 🌐 ColdFusion | 📅 2020-03-27 - Git hooks for CommandBox CFML based projects.
* [App::GitHooks](https://metacpan.org/pod/App::GitHooks) -  A modular and easy to configure git hooks framework, supporting many plugins.
* [Jig](https://pythonhosted.org/jig/) - A pre-commit hook on steroids.
* [hooks4git](https://pypi.org/project/hooks4git/) - A simple, flexible and language agnostic git hook management approach.

## Articles

* [Official Documentation](https://git-scm.com/docs/githooks)
* [Git Hooks (Part I): The Basics](http://omerkatz.com/blog/2013/2/15/git-hooks-part-1-the-basics)
* [Git Hooks (Part II): Implementing Git Hooks using Python](http://omerkatz.com/blog/2013/5/23/git-hooks-part-2-implementing-git-hooks-using-python)
* [Atlassian Git Hooks tutorial](https://ru.atlassian.com/git/tutorials/git-hooks)
* [Tips for using Git pre commit hook](https://codeinthehole.com/tips/tips-for-using-a-git-pre-commit-hook/)
* [Use a boostrap shell script to use Git Hooks in Mac with PowerShell and with IntelliJ](https://wilsonmar.github.io/git-hooks/)
* [githooks.com](https://githooks.com)
* [How To Use Git Hooks To Automate Development and Deployment Tasks](https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks)
* [Automate your workflow with git hooks
  ](https://medium.com/backticks-tildes/how-to-automate-your-git-workflow-with-git-hooks-c905296c49bc)
* [Automate your development workflow](https://medium.com/the-andela-way/git-hooks-beautifully-automate-tasks-stages-bfb29f42fea1)
* [Deploying websites with a Git hook](http://ryanflorence.com/deploying-websites-with-a-tiny-git-hook/)
* [The missing Git hooks documentation](https://longair.net/blog/2011/04/09/missing-git-hooks-documentation/)

## Video Tutorials

* [Introduction to Git Hooks](https://www.youtube.com/watch?v=8-JL6NOTZOw)
* [Git hooks, practical uses (yes, even on Windows)](https://www.youtube.com/watch?v=fMYv6-SZsSo)
* [Life’s better with Git hooks](https://www.youtube.com/watch?v=RG26-Iozg70)
* [Husky and the Git Hooks](https://www.youtube.com/watch?v=EpxkBgd8yq8)

## Support

If you have a question, find a bug, or just want to say hi, please open an [issue on GitHub](https://github.com/aitemr/awesome-git-hooks/issues/new) ⭐ 976 | 🐛 3 | 🌐 Shell | 📅 2026-01-19. If you want to contribute, please read the [guide](./contributing.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Islam Temirbek](https://aitemr.github.io) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
