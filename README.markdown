Nachos
================================

Because everyone loves Nachos!

Sync your watched repos with GitHub.  Manage them and stuff.  Never leave wifi again without all the codes you care about, local.

And more.

Workflow
================================
* watch a project on GitHub
* run 'nachos sync'
* magic - it is now up to date in your local repo and ready to go

Prerequisites
================================
    gem install octopussy
    gem install git-hub -v 1.4.1
    # go to your GitHub / "Account Settings" / "Account Admin" page to learn your API key
    git config --global github.user [your-github-account-name]
    git config --global github.token [your-github-api-key]

Release
================================
* bump version in version.rb
* commit and push
* run `rake release` to tag, push, and push gem

Note on Patches/Pull Requests
================================
* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.

Copyright
--------------------------------
Copyright (c) 2010 Rob Sanheim. See LICENSE for details.
