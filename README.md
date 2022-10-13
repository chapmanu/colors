# Chapman SMC Colors

Generate a graph showing everybody in your meeting's primary communication preferences

Located at [colors.chapman.edu](http://colors.chapman.edu). (not yet!)

### Development Environment Setup

This is as simple as it gets. Clone the repository locally, navigate to the project folder, and run `php -S localhost:8000`

### Deployment:

Colors is hosted on GitHub pages which publishes from the `gh-pages` branch.
After changes are merged into the `master` branch, bring changes into `gh-pages` branch.

    # From the master brach:
    git pull origin master
    git checkout gh-pages
    git merge master
    git push origin gh-pages
