Get Localization CLI
============

## Getting started ##

<pre>sudo pip install gl</pre>

## Basics ##

With Get Localization CLI you can push and pull translation files. 

<pre>
usage: gl <command> [options]

commands:

 add           Add new master file to project. It will be tracked and pushed when there's changes.
 init          Create a local repository to working directory and link it to existing Get Localization project.
 map-locale    Map translation of a given master file to local file. When file is pulled from server, it's saved to given target file.
 pull          Pull available translations from server
 push          Push changed master files to server
 push-tr       Push local mapped translations that do not exist on server
 remote        Return remote project name
 status        Project status
 translations  List translations from given project
</pre>

## Init project ##

  $ gl init [project-name]
  Repository created...
  
project-name  project name should match with your project name on Get Localization server: https://www.getlocalization.com/[project-name]/
 
Creates Get Localization repository to current directory. Repository meta-data is saved under .gl folder. This can be added to your version control (git, hg, svn etc). If you need different configuration for different branches, it's possible.

## Adding files ##



## Mapping locales ##
## Branching with version control ##
## Pushing (push) and pushing translations (push-tr) ##

