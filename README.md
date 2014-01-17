# Goto

A command line utility to aid speedy navigation around a Magento install.

# Installation

    brew tap meanbee/tap
    brew install goto
    Usage: goto command [param]

# Usage
    goto command [param]

Commands can be one of the following:

 	root 			    cd into the root directory of your installation.
 	app 			    cd into the app/ directory.
 	skin [theme] 		cd into the skin/ directory. If theme is provided cd into skin/frontend/theme/default.
 	design [theme] 		cd into the app/design directory. If theme is provided cd into app/design/frontend/theme/default.
 	frontend [theme] 	cd into the app/design/frontend/ directory. If theme is provided cd into app/design/frontend/theme/default.
 	template theme 		cd into the app/design/frontend/theme/default/template/ directory.
 	layout theme 		cd into the app/design/frontend/theme/default/layout/ directory.
 	code [codepool] 	cd into the app/code/codepool directory. Can be local, community or core.
 	modman [module] 	cd into the .modman directory. If module is provided cd into .modman/module/.
 	log 			    cd into the var/log/ directory.
 	switch [package] 	cd into another package, with the eqiuvilant path to your current working directory. If package is provided use this package, use 'base' otherwise.
 	help 			    print this usage message.
