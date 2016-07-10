# qooxdoo-wiki

This is the qooxdoo wiki development area. The wiki for
[qooxdoo](http://github.com/qooxdoo/qooxdoo) is developed here, and when
changes have been accepted, are applied to the [qooxdoo
wiki](http://github.com/qooxdoo/qooxdoo/wiki).

## Proposing qooxdoo wiki changes

In order to maintain the integrity of the wiki, it is edited collaboratively
in this repository. When changes have been accepted here, a member of the
commit team will push the changes to the [qooxdoo
wiki](https://github.com/qooxdoo/qooxdoo/wiki). Anyone wishing to propose
changes to the wiki may use the following process:

- Install [gollum](https://github.com/gollum/gollum) by following its
  [installation
  instructions](https://github.com/gollum/gollum/wiki/Installation).
- Fork this qooxdoo-wiki repository
- Clone your copy of this qooxdoo-wiki repository to your development system
- Create a [feature branch (_TODO_)]() in which you will make your edits. Note
  your feature branch's name. For our purposes here, let's say it's called
  _begin-user-docs_.
- Run gollum, referencing the feature branch name, e.g., `gollum --ref
  begin-user-docs`. It is **very important** to specify the branch name, as
  gollum will write changes directly to your github repository, in the branch
  specified here.
- Make your edits to the wiki in gollum. Be sure they are saved. Saving
  changes in gollum automatically commits those changes to the specified
  branch of the repository.
- Every change that was saved during the editing session was saved as a
  separate commit to the repository. Rather than proposing changes that
  include many commits, for documentation, it is preferable to _squash_ those
  many commits into a single commit. Carefully [review this squash
  procedure](https://robots.thoughtbot.com/git-interactive-rebase-squash-amend-rewriting-history)
  and then squash your numerous edit-session commits down to a single commit
  with a meaningful commit message.
- Push your feature branch to your personal qooxdoo-wiki repository on github.
- Issue a pull request from your branch to the upstream qooxdoo-wiki
  repository at https://github.com/qooxdoo/qooxdoo-wiki.
