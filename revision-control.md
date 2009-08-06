# motivation

* communication with the team
* ability to go back in time
* makes it easy to try different things (branches)

# use a distributed revision control system

* replicated history (redundancy)
* offline contribution (therefore also faster operations)
* encourages working with branches
* major open source projects use them/are switching
  * git
    * rails
    * yui
    * android
    * perl
    * wine
    * fedora
    * vlc
    * linux
    * gnome
    * x.org
  * bazaar (bzr)
    * mysql
    * squid
    * mailman
    * ubuntu
  * mercurial (hg)
    * python
    * mozilla
    * openjdk
    * opensolaris
    * xen

# commit messages

* atomic commits
  * this helps a lot!
  * makes it easier to describe a change and to keep the commit message sane
  * searching will be easier too
  * django calls them most granular change that makes sense
  * git's staging area eases forming atomic commits (look for best practices for svn, hg, bzr)
    * bzr has something called shelves
    * other systems usually support explicit naming of changed files (hg commit file1 file2 file3)
* describe why the change happened, not what it does (similar to how good comments work)
* don't be too verbose
* minor things that can help
  * use past tense instead of present tense (django recommendation)

## todo:

  * examples for good and bad commit messages?

## references 

* http://www.wildbit.com/blog/2008/11/11/the-importance-of-commit-messages/
* http://docs.djangoproject.com/en/dev/internals/contributing/#committing-code
* http://lbrandy.com/blog/2009/03/writing-better-commit-messages/
* http://drupal.org/node/52287
* http://wiki.scummvm.org/index.php/Commit_Guidelines

# push changes to the team

* why (this section needs improvement -> better reasons)
  * it is more convenient (removes a barrier)
  * encourages the team to look at changes done by other team members
  * leads people to write cleaner code if people are notified about changes

* push mechanisms
  * email
  * atom or rss feeds
  * xmpp
  * probably mention systems that already have support for push notifications
    * trac?
    * redmine?
    * fogbugz?
    * mantis?

