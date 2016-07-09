# Discussion list

# Proposing changes to qooxdoo

## Preparation

_describe how to fork and clone the qooxdoo repository, and any other prerequisites_

## Feature branches

_describe the process of creating a unique branch for a specific feature_

## Requesting that your proposed changes be incorporated

- Ensure that if your proposed changes alter or extend functionality of qooxdoo, that you also provide tests to show that the changes both work properly and are backward-compatible.
  - If the changes are not backward-compatible, discuss on the Discussion List how to resolve it. Likely, you will be asked to create a new function to implement the new functionality, and possibly mark the original function as deprecated.
- Be sure you have created a separate, feature branch, for your proposed changes. Any modification done to the branch after your impending pull request has been issued will be applied to the pull request, so you need to be sure that you aren't making unrelated changes to that same branch after your pull request has been made.
- Push your committed branch to your github repository.
- From the github web page of your repository, use the Pull Request button, and select your feature branch that includes the proposed changes.
  - _(describe this process in more detail)_

## Merge process

When a pull request (PR) is issued, all interested parties should express any concerns they have about the PR, by adding comments to the PR. The commit team (members wth write-access to the repository) will generally wait for at least one full business day (Mon - Fri) before beginning voting to accept the PR, to provide time for people to comment.

Acceptance of a PR is accomplished as follows:

- When the stream of comments has died down -- in particular, dissenting comments -- a member of the commit team will announce, in the PR, to begin voting.
- The commit team members vote to incorporate the PR by adding, to the _call for votes_ comment, a thumbs-up emoji, or vote against incorporating the PR by adding, to the _call for votes_ comment, a thumbs-down emoji. Votes against incorporating the PR must include an added comment explaining why the member is voting against incorporating the PR.
- If the PR proposer is a member of the commit team, he/she does not have voting rights on this PR.
- A PR will be accepted when one of the following conditions has been met:
  - PR contains only documentation changes
    - two assenting votes have been cast with no dissenting votes.
  - PR contains any code changes
    - five assenting votes have been cast with no dissenting votes
    - at least two business days have passed since the call for votes, and two assenting votes have been cast with no dissenting votes
- If there are dissenting votes (thumbs-down) during the voting process, discussion will ensue and a new vote will be called when the points of conflict have been resolved. _(when there are more committers, we could end up with an equal number of thumbs-up and thumbs-down. who makes the final decision? probably tobias?)_
- If this PR fixes a bug that should be cherry-picked into a point release, it is the responsibility of the person merging the PR to cherry-pick this set of commits into the point release branch (possibly creating that point release branch if it did not previously exist).
