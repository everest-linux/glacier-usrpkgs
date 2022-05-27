# glacier-usrpkgs
User packages collection for Glacier

User packages should contain the following:

- License
- Package source tree
- usrbuild.sh
- usrupdate.sh
- usrremove.sh
- pkgname.ts.sh (containing the same 2 lines as a regular Glacier package)
- pkgname-pkginfo.json (1 extra line reading `"is-usrpkg:" "yes",`)

A user package should create all the same files that a regular Glacier package would
