An example of using CI for Haxe projects.


Same procedure is used for setting up both [Travis CI](https://travis-ci.org/) and [AppVeyor](http://www.appveyor.com/):
 1. Create a Haxe project if there isn't one.
 2. Create a new repo on Github.
 3. Turn on the switches for the Github repo on Travis CI/AppVeyor.
 4. Copy and modify the configs:
     * [.travis.yml](.travis.yml) for Travis CI
     * [appveyor.yml](appveyor.yml) for AppVeyor
 5. Commit the configs and push to Github.
 6. Watch it build:
     * `https://travis-ci.org/${username}/${reponame}` for Travis CI
     * `https://ci.appveyor.com/project/${username}/${reponame}` for AppVeyor
 7. Add badges to README:
     * `https://travis-ci.org/${username}/${reponame}.svg?branch=master` for Travis CI
     * `https://ci.appveyor.com/api/projects/status/github/${username}/${reponame}?branch=master&svg=true` for AppVeyor
