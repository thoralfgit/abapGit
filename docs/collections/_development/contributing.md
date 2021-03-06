---
title: Contributing
order: 5
---

*******************************

1: Install the development version of abapGit by cloning the repository using an online repository, or downloading the zip file and installing it using an offline repository.

2: The abapGit report installed in your system will now consist of multiple classes

3: Do the required changes to classes and/or main program

4: Create the pull request with the changes

5: After the pull request is merged, abapmerge will automatically run to build the report version of abapGit.

Every time a commit is pushed to the master branch, [Travis CI](https://travis-ci.org/) will be triggered to perform the build. It will use [abapmerge](https://github.com/larshp/abapmerge) to merge all the includes into a single file, the build can be downloaded from [https://raw.githubusercontent.com/abapGit/build/master/zabapgit.abap](https://raw.githubusercontent.com/abapGit/build/master/zabapgit.abap)

Alternatively, use the GitHub webinterface to change the files and submit a pull request.
