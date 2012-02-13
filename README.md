About
=====

See the homepage for details.

TODO: link

Setting up
==========

Clone the project and setting it up for publishing:

    git clone git@github.com:yet-another-project/yet-another-project.github.com.git
    cd yet-another-project.github.com/
    git co -b src origin/src
    mv hooks/commit-msg .git/hooks/
    install Phrozn

To edit the website, edit files in `.phrozn/`, then commit the changes.
They will be automatically published in the `master` branch.

Do not forget to `git push` the changes.
