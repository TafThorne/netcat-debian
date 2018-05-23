# How to Contribute

## What Should I Know Before I Get Started?

This is a set of Dockerfiles to generate a Debian based Docker Image with the
netcat utility installed.  You can find more about these two projects on their
own pages:
* Debian - https://www.debian.org/intro/about
* netcat - http://man.openbsd.org/nc

## How Can I Contribute?

### Reporting Bugs

Please file a bug under the netcat-debian GitHub project.  Make sure to
describe what you were doing when you provoked the bug.  If possible provide
example commands to recreatea it and the output given at the time of the error.

### Suggesting Enhancements
### Your First Code Contribution

Please ensure that you build an Docker Image to test your new Dockerfile:
 docker build -t tafthorne/netcat-debian -f ./Dockerfile .

### Pull Requests

## Styleguides

### Git Commit Messages

Summary line of up to ~50 chracters written in the style of completing the
sentence "This commit will...".  It should be more about the 'what' than the
'why'.  Do not put a full stop at the end of the summary line.  Please Use
Title Caps.

Write the whole message in the impretative.

Assume some poor soul is using a plain text system and needs you to line wrap
your commit message at 72 charaters for them.  If you have some example output
then it is OK to recreate it verbatum but please wrape your prose.

In the body try to mention:
* Why you are making the change
* Why you did not make some obvious alterative changes (if applicable)
* What other things you tried before getting this change to work (as previous)
* If you know or suspect a wrack in the grass please warn about it
* If this alters some output please put a before and after example in (that
includes you eliminating some error output with a fix)

If there is a ticket number or bug title relating to the fix, please include it
in the body.

For some explination of why these guidelines, please read taggery's A Note
About Git Commit Messages blog post:

https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

and Chris Beams' How to Write a Git Commit Message:

https://chris.beams.io/posts/git-commit/

If you would like a more verbose set of examples then the OpenStack post on 
Git Commit Messags provide nice set of good and bad examples:

https://wiki.openstack.org/wiki/GitCommitMessages

### JavaScript Styleguide
### CoffeeScript Styleguide
### Specs Styleguide
### Documentation Styleguide

## Additional Notes
### Issue and Pull Request Labels

