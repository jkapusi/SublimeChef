SublimeChef
===========

A Sublime Text 2 Package for authoring Chef related files.

This Package provides several code snippets designed to make writing chef recipes faster and even more fun. 
Each snippet has sensible defaults, carefully chosen placeholders, and several variations to cover almost all of your recipe needs.

Maybe this is better explained with a [youtube demo video](http://www.youtube.com/watch?v=4VtDj_ar1Xg).


Install
-------

If you have Package Control installed in Sublime Text the following steps are needed:
* press ctrl+shift+p (Windows, Linux) or cmd+shift+p (OS X) to open Command Pallete
* start typing 'repository' to select 'Package Control: Add Repository'
* paste github url: https://github.com/jkapusi/SublimeChef
* open the Command Pallete again (ctrl+shift+p or cmd+shift+p)
* start typing 'install' to select 'Package Control: Install package'
* start typing 'chef' and find the repository name in the description (there is multiple package with the same name, so make sure you selected the right one)

Differences from the original
-----------------------------

	crond (https://github.com/chef-cookbooks/cron/blob/master/providers/d.rb)

Completions
-----------

These are the available completions:

    actionn
    ignoref
	provider
	retries
	supports
	not_ifd
	not_if
	only_ifd
	only_if
	cookbook_filef
	cookbook_file
	cronf
	cron
	deploy
	directoryf
	directoryr
	directory
	env
	erl_call
	executef
	executen
	execute
	filec
	filef
	file
	groupa
	group
	http_requestp
	http_request
	include_recipe
	linkf
	linkh
	link
	logd
	log
	mdadm
	metadataf
	metadata
	mountf
	mountl
	mountn
	mount
	notifiesi
	notifies
	subscribesi
	subscribes
	ohaip
	ohai
	packageo
	packager
	packagev
	package
	remote_filef
	remote_filem
	remote_file
	remote_directoryf
	remote_directory
	ruby_block
	git
	subversion
	bash
	perl
	python
	role
	ruby
	script
	servicep
	service
	templatev
	template
	user