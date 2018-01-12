# UpdateLibraryChecklist
Checklist on how to update a library

- [ ] Make your code changes
- [ ] Update README if needed
- [ ] Bump version of the project (all targets, ex tvOS, macOS etc)
- [ ] Update the version number in the Podspec file
- [ ] Run `carthage build --no-skip-current`
- [ ] run `carthage archive <PorductName>`
- [ ] Commit your changes
- [ ] Tag release `git tag -a X.X.X -m "Message"`
- [ ] Push the tags `git push --tags`
- [ ] Create a release form the tag on Github and attach zipped framework
- [ ] Push Cocoapods version with `pod trunk push`

