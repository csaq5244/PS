# CONTINUOUS INTEGRATION

Continuous integration involves integrating early and often, so as to avoid the pitfalls of "integration/merge hell". The practice aims to reduce rework and thus reduce cost and time. The workflow of continuous integration consists of: keep commits small and check in frequently, only check in not broken and tested code, don’t check in if the build is broken. Before submitting work, each programmer must do a complete build and run (and pass) all unit tests. Integration tests are usually run automatically on a CI server when it detects a new commit. All programmers should start the day by updating the project from the repository. That way, they will all stay up to date.

###Benefits
-	Maintain a single source repository
-	Automate the build
-	Make your build self-testing
-	Keep the build fast
-	Make it easy for anyone to get the latest executable
-	Everyone can see what’s happening
-	Automate deployment

###Downsides
- Time overhead
- Build needs to be fast, because for every commit the CI server runs a new build
-Team needs to be trained, easy to do CI wrong/inefficent




