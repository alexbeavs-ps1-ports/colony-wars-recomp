# Release preparation

2026-09-06: Prepared a portable setup recipe from accepted framework `c14a8e8a9926b3354fa5a7324b84858b959017a4`.
The release snapshot keeps functional code and title seed bytes, adds the bounded setup backport, and excludes private input/history.
Consulted the local release process, PSX-PUB-016, the accepted title handoff, and [Git orphan-branch documentation](https://git-scm.com/docs/git-checkout).
The shared archive gate now accepts only exact hashes for two intentional SDK path-example files; changed and relocated fixtures still fail.
Native CI and Windows package acceptance are pending.
