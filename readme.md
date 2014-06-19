# VVV Auto Bootstrap Simple

This is one of a series of demonstrations of the auto-sitesetup designed to be used with [Varying Vagrants Vagrant](https://github.com/10up/varying-vagrant-vagrants/).

This demo shows a site setup using Composer and some WP CLI commands; this one's for [Rarst](http://composer.rarst.net/).

To get started:

1. If you don't already have it, clone the [Vagrant repo](https://github.com/10up/varying-vagrant-vagrants/) , perhaps into your `~/Vagrants/` directory (you may need to create it if it doesn't already exist)
2. Install the Vagrant hosts updater: `vagrant plugin install vagrant-hostsupdater`
3. Clone this branch of this repo into the `www` directory of your Vagrant as `www/PROJECTNAME`
4. If your Vagrant is running, from the Vagrant directory run `vagrant halt`
5. Run a search and replace for vvv-simple, and replace with your PROJECTNAME
6. Followed by `vagrant up --provision`.  Perhaps a cup of tea now? The provisioning may take a while.

Then you can visit [http://PROJECTNAME.dev/](http://PROJECTNAME.dev/)S
