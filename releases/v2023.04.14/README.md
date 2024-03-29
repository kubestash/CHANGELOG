# KubeStash v2023.04.14 (2023-04-14)


## [kubestash/apimachinery](https://github.com/kubestash/apimachinery)

### [v0.1.0](https://github.com/kubestash/apimachinery/releases/tag/v0.1.0)

- [64a7ccb](https://github.com/kubestash/apimachinery/commit/64a7ccb) Update api for postgres manifest backup (#4)
- [b1e0b5e](https://github.com/kubestash/apimachinery/commit/b1e0b5e) Update deps
- [d1b2bd0](https://github.com/kubestash/apimachinery/commit/d1b2bd0) Fix fuzz testing (#3)
- [3a35447](https://github.com/kubestash/apimachinery/commit/3a35447) Add restic pkg (#2)
- [390d645](https://github.com/kubestash/apimachinery/commit/390d645) Add crd labels
- [466cb7d](https://github.com/kubestash/apimachinery/commit/466cb7d) Fix code structure (#1)
- [4ea467e](https://github.com/kubestash/apimachinery/commit/4ea467e) Support restoring particular manifest components. (#67)
- [916b38f](https://github.com/kubestash/apimachinery/commit/916b38f) Fix storage cleanup (#78)
- [8223391](https://github.com/kubestash/apimachinery/commit/8223391) Make resticStats and volumeSnapshotterStats fields pointer (#74)
- [795a95a](https://github.com/kubestash/apimachinery/commit/795a95a) Move Snapshot components from Status to Spec (#73)
- [cd983b2](https://github.com/kubestash/apimachinery/commit/cd983b2) Refactor Codebase + Fix Bugs  (#68)
- [a8bfc22](https://github.com/kubestash/apimachinery/commit/a8bfc22) Use ghcr.io/appscode/gengo (#69)
- [7022330](https://github.com/kubestash/apimachinery/commit/7022330) Fix formatting
- [a184e62](https://github.com/kubestash/apimachinery/commit/a184e62) Fix Restore job creation bugs. (#60)
- [290cdaa](https://github.com/kubestash/apimachinery/commit/290cdaa) Use ghcr.io (#64)
- [e5a2904](https://github.com/kubestash/apimachinery/commit/e5a2904) Use ghcr.io for appscode/golang-dev (#62)
- [2bd40c9](https://github.com/kubestash/apimachinery/commit/2bd40c9) Update go module to kubestash.dev/kubestash (#59)
- [7f2cc37](https://github.com/kubestash/apimachinery/commit/7f2cc37) Implement Cleanup for Snapshot components (#58)
- [bd4d450](https://github.com/kubestash/apimachinery/commit/bd4d450) Add Restic package. (#54)
- [26c2bec](https://github.com/kubestash/apimachinery/commit/26c2bec) Implement object existence checker (#55)
- [fdde479](https://github.com/kubestash/apimachinery/commit/fdde479) Add encryptionSecret ref to RestoreSession. (#52)
- [b64bd7f](https://github.com/kubestash/apimachinery/commit/b64bd7f) Remove crd-installer (#57)
- [3bead7e](https://github.com/kubestash/apimachinery/commit/3bead7e) Fix Makefile
- [597d76b](https://github.com/kubestash/apimachinery/commit/597d76b) Move charts to installer repo (#56)
- [4fb3bd0](https://github.com/kubestash/apimachinery/commit/4fb3bd0) Add Validation Webhook for BackupConfiguration (#51)
- [64c9ee2](https://github.com/kubestash/apimachinery/commit/64c9ee2) Update Backup Executor (#50)
- [411e641](https://github.com/kubestash/apimachinery/commit/411e641) Implement Snapshot pkg + Fix bugs (#49)
- [f28194f](https://github.com/kubestash/apimachinery/commit/f28194f) Add unit tests for Retention Policy (#47)
- [5d583e0](https://github.com/kubestash/apimachinery/commit/5d583e0) Implement addon-task resolver. (#44)
- [5fba517](https://github.com/kubestash/apimachinery/commit/5fba517) Add WalG driver specific information to Snapshot API (#45)
- [8d0723b](https://github.com/kubestash/apimachinery/commit/8d0723b) Implement Retention Policy (#46)
- [1c44e6c](https://github.com/kubestash/apimachinery/commit/1c44e6c) Use constants to improve code readability (#42)
- [85b2051](https://github.com/kubestash/apimachinery/commit/85b2051) Implement Backend Repository (#40)
- [b696376](https://github.com/kubestash/apimachinery/commit/b696376) Implement `trigger-backup` command. (#37)
- [35b3c49](https://github.com/kubestash/apimachinery/commit/35b3c49) Use `CreateOrPatch` instead of `CreateOrUpdate`. (#38)
- [c9806ec](https://github.com/kubestash/apimachinery/commit/c9806ec) Run GH actions on ubuntu-20.04 (#41)
- [9cc0e44](https://github.com/kubestash/apimachinery/commit/9cc0e44) Implement Backend package (#36)
- [34f61cc](https://github.com/kubestash/apimachinery/commit/34f61cc) Implement Scheduler package. (#35)
- [8b2aef0](https://github.com/kubestash/apimachinery/commit/8b2aef0) Add BackupSession controller. (#25)
- [da5ee12](https://github.com/kubestash/apimachinery/commit/da5ee12) Fix order of expected and actual value in unit tests (#34)
- [cf1233a](https://github.com/kubestash/apimachinery/commit/cf1233a) Add RestoreSession controller (#26)
- [58268ef](https://github.com/kubestash/apimachinery/commit/58268ef) Update Snapshot conditions (#30)
- [8716c64](https://github.com/kubestash/apimachinery/commit/8716c64) Use common method for getting object key (#29)
- [5bc5045](https://github.com/kubestash/apimachinery/commit/5bc5045) Use k8s 1.25 client libs (#28)
- [13d6d2c](https://github.com/kubestash/apimachinery/commit/13d6d2c) Move RetentionPolicy under Backends in BackupConfiguration api. (#24)
- [e876acf](https://github.com/kubestash/apimachinery/commit/e876acf) Add snapshot controller (#23)
- [df275b9](https://github.com/kubestash/apimachinery/commit/df275b9) Add BackupConfiguration controller. (#19)
- [2453e35](https://github.com/kubestash/apimachinery/commit/2453e35) Add Repository controller (#21)
- [ad2a78d](https://github.com/kubestash/apimachinery/commit/ad2a78d) Add BackupStorage controller (#18)
- [8b77b88](https://github.com/kubestash/apimachinery/commit/8b77b88) Add subjects field in BackupBlueprint (#16)
- [f3e0190](https://github.com/kubestash/apimachinery/commit/f3e0190) Update to k8s 1.24 toolchain (#15)
- [c4bfbf6](https://github.com/kubestash/apimachinery/commit/c4bfbf6) Allow cross-namespaced target reference + add timeout (#14)
- [5983453](https://github.com/kubestash/apimachinery/commit/5983453) Use Go 1.18 (#13)
- [cdfba44](https://github.com/kubestash/apimachinery/commit/cdfba44) Use Go 1.18 (#12)
- [1b5ee5d](https://github.com/kubestash/apimachinery/commit/1b5ee5d) make fmt (#6)
- [0648812](https://github.com/kubestash/apimachinery/commit/0648812) Make KubeStash deployable (#11)
- [30b4896](https://github.com/kubestash/apimachinery/commit/30b4896) Add validation and defaulting webhooks for new APIs (#10)
- [6d063dc](https://github.com/kubestash/apimachinery/commit/6d063dc) Fix code generation + Update Makefile (#9)
- [667bb60](https://github.com/kubestash/apimachinery/commit/667bb60) Fix CI (#8)
- [0fcdf19](https://github.com/kubestash/apimachinery/commit/0fcdf19) Add API types
- [046297a](https://github.com/kubestash/apimachinery/commit/046297a) Add missing licenses
- [a2cd573](https://github.com/kubestash/apimachinery/commit/a2cd573) Generate deepcopy methods for shared api types
- [f5899e3](https://github.com/kubestash/apimachinery/commit/f5899e3) code gen
- [2aadb4e](https://github.com/kubestash/apimachinery/commit/2aadb4e) Add kubebuilder markers
- [709d6a4](https://github.com/kubestash/apimachinery/commit/709d6a4) Fix gramatical errors
- [ff43370](https://github.com/kubestash/apimachinery/commit/ff43370) Add comments in Snapshot API
- [bc9c4b7](https://github.com/kubestash/apimachinery/commit/bc9c4b7) Add comment in RetentionPolicy API
- [3f3bd49](https://github.com/kubestash/apimachinery/commit/3f3bd49) Add comment in Repository API
- [787e9ea](https://github.com/kubestash/apimachinery/commit/787e9ea) Add comment in BackupStorage API
- [34b1d8d](https://github.com/kubestash/apimachinery/commit/34b1d8d) Add comments in RestoreSession API type
- [63d559d](https://github.com/kubestash/apimachinery/commit/63d559d) Add comment to the HookTemplate API type
- [4c90d9a](https://github.com/kubestash/apimachinery/commit/4c90d9a) Add comments to the BackupSession API type definition
- [f647345](https://github.com/kubestash/apimachinery/commit/f647345) Add comments for BackupConfiguration and BackupBatch APIs
- [cb2a8a6](https://github.com/kubestash/apimachinery/commit/cb2a8a6) Add comments explanation for type definition of BackupBatch
- [e848340](https://github.com/kubestash/apimachinery/commit/e848340) Add field specification for Addon API
- [4751b12](https://github.com/kubestash/apimachinery/commit/4751b12) Refactor API types
- [6874ef7](https://github.com/kubestash/apimachinery/commit/6874ef7) Add BackupBlueprint, BackupBatch, and RestoreSession types
- [824af2e](https://github.com/kubestash/apimachinery/commit/824af2e) WIP: Add core APIs
- [7ec382a](https://github.com/kubestash/apimachinery/commit/7ec382a) Add addon APIs
- [3b14ead](https://github.com/kubestash/apimachinery/commit/3b14ead) Add API types
- [ba38eb5](https://github.com/kubestash/apimachinery/commit/ba38eb5) Rename `backup`,`restore`, and `template` API groups into `core`
- [61beb6f](https://github.com/kubestash/apimachinery/commit/61beb6f) Replace Apache License with AppsCode License
- [ffd1575](https://github.com/kubestash/apimachinery/commit/ffd1575) Add BackupBlueprint and HookTemplate in core API group
- [97563a4](https://github.com/kubestash/apimachinery/commit/97563a4) Rename `backup`,`restore` API groups into `core`
- [a50b1d4](https://github.com/kubestash/apimachinery/commit/a50b1d4) Groups similar API resources into different groups
- [e61a350](https://github.com/kubestash/apimachinery/commit/e61a350) Bootstrap initial APIs



## [kubestash/installer](https://github.com/kubestash/installer)

### [v2023.04.14](https://github.com/kubestash/installer/releases/tag/v2023.04.14)

- [a253c01](https://github.com/kubestash/installer/commit/a253c01) Prepare for release v2023.04.14 (#7)
- [56ec6ba](https://github.com/kubestash/installer/commit/56ec6ba) Add update-chart-dependencies.sh script
- [b83ff35](https://github.com/kubestash/installer/commit/b83ff35) Import crds
- [33b1e06](https://github.com/kubestash/installer/commit/33b1e06) Update deps
- [0fee2ea](https://github.com/kubestash/installer/commit/0fee2ea) Use uid 65534 and test against K8s 1.27.0 (#6)
- [1ec4082](https://github.com/kubestash/installer/commit/1ec4082) Use ghcr.io/appscode/gengo (#5)
- [254dd7a](https://github.com/kubestash/installer/commit/254dd7a) Stop publishing charts to docker hub
- [b82c1ba](https://github.com/kubestash/installer/commit/b82c1ba) Test against k8s 1.26
- [71654d0](https://github.com/kubestash/installer/commit/71654d0) Use ghcr.io for appscode/golang-dev (#4)
- [da406db](https://github.com/kubestash/installer/commit/da406db) Add platform values
- [ebe68b6](https://github.com/kubestash/installer/commit/ebe68b6) Remove CRD installer (#3)
- [6d90d09](https://github.com/kubestash/installer/commit/6d90d09) Move charts from kubestash repo



## [kubestash/kubedb-manifest](https://github.com/kubestash/kubedb-manifest)

### [v0.1.0](https://github.com/kubestash/kubedb-manifest/releases/tag/v0.1.0)

- [b1a69b5](https://github.com/kubestash/kubedb-manifest/commit/b1a69b5) Prepare for release v0.1.0 (#5)
- [5344e9f](https://github.com/kubestash/kubedb-manifest/commit/5344e9f) Update modules (#4)
- [14b2797](https://github.com/kubestash/kubedb-manifest/commit/14b2797) Add CI badge
- [969eeda](https://github.com/kubestash/kubedb-manifest/commit/969eeda) Organize code structure (#3)
- [9fc3cbe](https://github.com/kubestash/kubedb-manifest/commit/9fc3cbe) Postgres manifest (#2)
- [8e2a56f](https://github.com/kubestash/kubedb-manifest/commit/8e2a56f) Merge pull request #1 from kubestash/mongodb-manifest
- [e80c1d0](https://github.com/kubestash/kubedb-manifest/commit/e80c1d0) update flag names.
- [80d3908](https://github.com/kubestash/kubedb-manifest/commit/80d3908) Add options for changing name in the restored files.
- [e7da42d](https://github.com/kubestash/kubedb-manifest/commit/e7da42d) Fix error.
- [70a0267](https://github.com/kubestash/kubedb-manifest/commit/70a0267) Sync with updated snapshot api
- [9d747d8](https://github.com/kubestash/kubedb-manifest/commit/9d747d8) Merge branch 'mongodb-manifest' of github.com:stashed/kubedb-manifest into mongodb-manifest
- [90e00e3](https://github.com/kubestash/kubedb-manifest/commit/90e00e3) Fix bugs.
- [9c3fc1e](https://github.com/kubestash/kubedb-manifest/commit/9c3fc1e) Sync with updated snapshot api
- [c321013](https://github.com/kubestash/kubedb-manifest/commit/c321013) update component path.
- [7f4bd17](https://github.com/kubestash/kubedb-manifest/commit/7f4bd17) Refactor.
- [2b61ff0](https://github.com/kubestash/kubedb-manifest/commit/2b61ff0) Specify component directory
- [6264cdf](https://github.com/kubestash/kubedb-manifest/commit/6264cdf) Support restoring particular mongo component.
- [0008570](https://github.com/kubestash/kubedb-manifest/commit/0008570) Fix restore component phase updating.
- [8bd4c95](https://github.com/kubestash/kubedb-manifest/commit/8bd4c95) Fix restore manifests.
- [7eda9f9](https://github.com/kubestash/kubedb-manifest/commit/7eda9f9) Update Snapshot phase calculation.
- [a2b52d2](https://github.com/kubestash/kubedb-manifest/commit/a2b52d2) Add core to runtime scheme.
- [9bd6bd5](https://github.com/kubestash/kubedb-manifest/commit/9bd6bd5) Fix bugs.
- [9e08774](https://github.com/kubestash/kubedb-manifest/commit/9e08774) Fix build
- [01225c6](https://github.com/kubestash/kubedb-manifest/commit/01225c6) Update module path
- [45d0e45](https://github.com/kubestash/kubedb-manifest/commit/45d0e45) updated flags.
- [fb0282f](https://github.com/kubestash/kubedb-manifest/commit/fb0282f) update docker file.
- [ad4c004](https://github.com/kubestash/kubedb-manifest/commit/ad4c004) refactor.
- [8f71d3a](https://github.com/kubestash/kubedb-manifest/commit/8f71d3a) Fix build
- [115ef23](https://github.com/kubestash/kubedb-manifest/commit/115ef23) update makefile.
- [a274690](https://github.com/kubestash/kubedb-manifest/commit/a274690) update backup and restore.
- [cff449f](https://github.com/kubestash/kubedb-manifest/commit/cff449f) Use yaml pkg from k8s.io.
- [dcbb399](https://github.com/kubestash/kubedb-manifest/commit/dcbb399) Use restic package from KubeStash.
- [596a498](https://github.com/kubestash/kubedb-manifest/commit/596a498) fix restore implementation.
- [6ebc19b](https://github.com/kubestash/kubedb-manifest/commit/6ebc19b) Implement restore.
- [3e8a869](https://github.com/kubestash/kubedb-manifest/commit/3e8a869) Start implementing restore.
- [e841113](https://github.com/kubestash/kubedb-manifest/commit/e841113) Add backup methods for mongodb.
- [b5961f7](https://github.com/kubestash/kubedb-manifest/commit/b5961f7) Continue implementing backup.
- [d943f6a](https://github.com/kubestash/kubedb-manifest/commit/d943f6a) Implement manifest backup for MongoDB.
- [e644c67](https://github.com/kubestash/kubedb-manifest/commit/e644c67) Implement kubedb-manifest plugin to MongoDB manifests.



## [kubestash/kubestash](https://github.com/kubestash/kubestash)

### [v0.1.0](https://github.com/kubestash/kubestash/releases/tag/v0.1.0)

- [d1aa78a](https://github.com/kubestash/kubestash/commit/d1aa78a) Prepare for release v0.1.0 (#86)
- [8a72f44](https://github.com/kubestash/kubestash/commit/8a72f44) Update Resolver for postgres manifest backup (#85)
- [cd79664](https://github.com/kubestash/kubestash/commit/cd79664) Fix test (#84)
- [5f166bc](https://github.com/kubestash/kubestash/commit/5f166bc) Use updated api (#83)
- [314bb0a](https://github.com/kubestash/kubestash/commit/314bb0a) Update restic modules (#82)
- [e0c5746](https://github.com/kubestash/kubestash/commit/e0c5746) Remove restic pkg (#81)
- [3ffc633](https://github.com/kubestash/kubestash/commit/3ffc633) Use kubestash/apimachinery (#79)
- [b268f84](https://github.com/kubestash/kubestash/commit/b268f84) Support restoring particular manifest components. (#67)
- [16ed157](https://github.com/kubestash/kubestash/commit/16ed157) Fix storage cleanup (#78)
- [aaa268a](https://github.com/kubestash/kubestash/commit/aaa268a) Use uid 65534 and test against K8s 1.27.0 (#77)
- [77154e5](https://github.com/kubestash/kubestash/commit/77154e5) Fix unit tests + Resolve bugs (#76)
- [71025a4](https://github.com/kubestash/kubestash/commit/71025a4) Update rbac + Fix snapshot cleanup + Fix bugs (#75)
- [3c9d996](https://github.com/kubestash/kubestash/commit/3c9d996) Make resticStats and volumeSnapshotterStats fields pointer (#74)
- [db82308](https://github.com/kubestash/kubestash/commit/db82308) Move Snapshot components from Status to Spec (#73)
- [99f5e94](https://github.com/kubestash/kubestash/commit/99f5e94) Add a nil check for jobtemplate before setting service account (#72)
- [8aef4b3](https://github.com/kubestash/kubestash/commit/8aef4b3) Set user provided service account for backup and restore job (#71)
- [48eb367](https://github.com/kubestash/kubestash/commit/48eb367) Refactor Codebase + Fix Bugs  (#68)
- [ffe5b07](https://github.com/kubestash/kubestash/commit/ffe5b07) Use ghcr.io/appscode/gengo (#69)
- [81febbe](https://github.com/kubestash/kubestash/commit/81febbe) Fix formatting
- [e4de498](https://github.com/kubestash/kubestash/commit/e4de498) Fix Restore job creation bugs. (#60)
- [ae8e82d](https://github.com/kubestash/kubestash/commit/ae8e82d) Unlock if prune fails for locked repository (#65)
- [118689c](https://github.com/kubestash/kubestash/commit/118689c) Create local directory when initializing the restic repository (#63)
- [17f698f](https://github.com/kubestash/kubestash/commit/17f698f) Use ghcr.io (#64)
- [e6ca9d6](https://github.com/kubestash/kubestash/commit/e6ca9d6) Use ghcr.io for appscode/golang-dev (#62)
- [781e4e3](https://github.com/kubestash/kubestash/commit/781e4e3) Fix restore related bugs (#61)
- [5e9b1ed](https://github.com/kubestash/kubestash/commit/5e9b1ed) Update go module to kubestash.dev/kubestash (#59)
- [2e77c7e](https://github.com/kubestash/kubestash/commit/2e77c7e) Implement Cleanup for Snapshot components (#58)
- [b52db0d](https://github.com/kubestash/kubestash/commit/b52db0d) Add Restic package. (#54)
- [29146b9](https://github.com/kubestash/kubestash/commit/29146b9) Implement object existence checker (#55)
- [e1cdc29](https://github.com/kubestash/kubestash/commit/e1cdc29) Add encryptionSecret ref to RestoreSession. (#52)
- [1396ce9](https://github.com/kubestash/kubestash/commit/1396ce9) Handle Repository conflict error in Backend (#53)
- [1c8d7a1](https://github.com/kubestash/kubestash/commit/1c8d7a1) Remove crd-installer (#57)
- [ec1e585](https://github.com/kubestash/kubestash/commit/ec1e585) Fix Makefile
- [236b4db](https://github.com/kubestash/kubestash/commit/236b4db) Move charts to installer repo (#56)
- [e1efc75](https://github.com/kubestash/kubestash/commit/e1efc75) Add Validation Webhook for BackupConfiguration (#51)
- [2fe8d37](https://github.com/kubestash/kubestash/commit/2fe8d37) Update Backup Executor (#50)
- [b83f510](https://github.com/kubestash/kubestash/commit/b83f510) Implement Snapshot pkg + Fix bugs (#49)
- [57da091](https://github.com/kubestash/kubestash/commit/57da091) Add unit tests for Retention Policy (#47)
- [5a32eee](https://github.com/kubestash/kubestash/commit/5a32eee) Implement addon-task resolver. (#44)
- [934dd3f](https://github.com/kubestash/kubestash/commit/934dd3f) Update Snapshot phase in BackupSession status (#48)
- [73035e0](https://github.com/kubestash/kubestash/commit/73035e0) Add WalG driver specific information to Snapshot API (#45)
- [d5a99dd](https://github.com/kubestash/kubestash/commit/d5a99dd) Implement Retention Policy (#46)
- [f738edb](https://github.com/kubestash/kubestash/commit/f738edb) Implement Backend snapshot (#43)
- [bbd9d60](https://github.com/kubestash/kubestash/commit/bbd9d60) Use constants to improve code readability (#42)
- [e9baa5c](https://github.com/kubestash/kubestash/commit/e9baa5c) Implement Backend Repository (#40)
- [a5f7559](https://github.com/kubestash/kubestash/commit/a5f7559) Implement `trigger-backup` command. (#37)
- [e0adbe4](https://github.com/kubestash/kubestash/commit/e0adbe4) Use `CreateOrPatch` instead of `CreateOrUpdate`. (#38)
- [961aed8](https://github.com/kubestash/kubestash/commit/961aed8) Patch status instead of update. (#39)
- [7bf02f8](https://github.com/kubestash/kubestash/commit/7bf02f8) Run GH actions on ubuntu-20.04 (#41)
- [2354272](https://github.com/kubestash/kubestash/commit/2354272) Implement Backend package (#36)
- [70aa927](https://github.com/kubestash/kubestash/commit/70aa927) Implement Scheduler package. (#35)
- [226588e](https://github.com/kubestash/kubestash/commit/226588e) Add BackupSession controller. (#25)
- [e42e28c](https://github.com/kubestash/kubestash/commit/e42e28c) Fix order of expected and actual value in unit tests (#34)
- [08a8468](https://github.com/kubestash/kubestash/commit/08a8468) Add RestoreSession controller (#26)
- [977f4fc](https://github.com/kubestash/kubestash/commit/977f4fc) Rename backupConfigHandler to bCReconciler and update logger levels. (#32)
- [5f40b36](https://github.com/kubestash/kubestash/commit/5f40b36) Return error from reconciler if fail to update status + Refactor Unit tests (#33)
- [c2e7804](https://github.com/kubestash/kubestash/commit/c2e7804) Pass context as a parameter (#31)
- [782f499](https://github.com/kubestash/kubestash/commit/782f499) Update Snapshot conditions (#30)
- [adf5fe6](https://github.com/kubestash/kubestash/commit/adf5fe6) Use common method for getting object key (#29)
- [4566431](https://github.com/kubestash/kubestash/commit/4566431) Refactor unit tests (#27)
- [7459f03](https://github.com/kubestash/kubestash/commit/7459f03) Use k8s 1.25 client libs (#28)
- [703f1b9](https://github.com/kubestash/kubestash/commit/703f1b9) Move RetentionPolicy under Backends in BackupConfiguration api. (#24)
- [f0b97f5](https://github.com/kubestash/kubestash/commit/f0b97f5) Add snapshot controller (#23)
- [a2eeb4e](https://github.com/kubestash/kubestash/commit/a2eeb4e) Add BackupConfiguration controller. (#19)
- [e4650f0](https://github.com/kubestash/kubestash/commit/e4650f0) Add Repository controller (#21)
- [f90262d](https://github.com/kubestash/kubestash/commit/f90262d) Remove unnecessary logs and update conditions of BackupStorage (#22)
- [dd771ba](https://github.com/kubestash/kubestash/commit/dd771ba) Add BackupStorage controller (#18)
- [c97a7a4](https://github.com/kubestash/kubestash/commit/c97a7a4) Add interface in storage (#20)
- [a4cde47](https://github.com/kubestash/kubestash/commit/a4cde47) Add high level packages and their methods (#17)
- [1f1096c](https://github.com/kubestash/kubestash/commit/1f1096c) Add subjects field in BackupBlueprint (#16)
- [d49fea2](https://github.com/kubestash/kubestash/commit/d49fea2) Update to k8s 1.24 toolchain (#15)
- [73e6506](https://github.com/kubestash/kubestash/commit/73e6506) Allow cross-namespaced target reference + add timeout (#14)
- [3b3eff3](https://github.com/kubestash/kubestash/commit/3b3eff3) Use Go 1.18 (#13)
- [4086ac6](https://github.com/kubestash/kubestash/commit/4086ac6) Use Go 1.18 (#12)
- [ce7e463](https://github.com/kubestash/kubestash/commit/ce7e463) make fmt (#6)
- [781e82a](https://github.com/kubestash/kubestash/commit/781e82a) Make KubeStash deployable (#11)
- [e765b60](https://github.com/kubestash/kubestash/commit/e765b60) Add validation and defaulting webhooks for new APIs (#10)
- [52e3b69](https://github.com/kubestash/kubestash/commit/52e3b69) Fix code generation + Update Makefile (#9)
- [6ca2cdf](https://github.com/kubestash/kubestash/commit/6ca2cdf) Fix CI (#8)
- [43ea210](https://github.com/kubestash/kubestash/commit/43ea210) Add API types
- [dbcf917](https://github.com/kubestash/kubestash/commit/dbcf917) Add missing licenses
- [b38e42b](https://github.com/kubestash/kubestash/commit/b38e42b) Generate deepcopy methods for shared api types
- [46604b8](https://github.com/kubestash/kubestash/commit/46604b8) code gen
- [971700e](https://github.com/kubestash/kubestash/commit/971700e) Add kubebuilder markers
- [c3417ad](https://github.com/kubestash/kubestash/commit/c3417ad) Fix gramatical errors
- [8b546b2](https://github.com/kubestash/kubestash/commit/8b546b2) Add comments in Snapshot API
- [7649e27](https://github.com/kubestash/kubestash/commit/7649e27) Add comment in RetentionPolicy API
- [9f3de86](https://github.com/kubestash/kubestash/commit/9f3de86) Add comment in Repository API
- [6985ed1](https://github.com/kubestash/kubestash/commit/6985ed1) Add comment in BackupStorage API
- [97fb658](https://github.com/kubestash/kubestash/commit/97fb658) Add comments in RestoreSession API type
- [6967919](https://github.com/kubestash/kubestash/commit/6967919) Add comment to the HookTemplate API type
- [a606560](https://github.com/kubestash/kubestash/commit/a606560) Add comments to the BackupSession API type definition
- [ea8fc37](https://github.com/kubestash/kubestash/commit/ea8fc37) Add comments for BackupConfiguration and BackupBatch APIs
- [3065830](https://github.com/kubestash/kubestash/commit/3065830) Add comments explanation for type definition of BackupBatch
- [4c3ab59](https://github.com/kubestash/kubestash/commit/4c3ab59) Add field specification for Addon API
- [70862e3](https://github.com/kubestash/kubestash/commit/70862e3) Refactor API types
- [ea88e6d](https://github.com/kubestash/kubestash/commit/ea88e6d) Add BackupBlueprint, BackupBatch, and RestoreSession types
- [dfc27d3](https://github.com/kubestash/kubestash/commit/dfc27d3) WIP: Add core APIs
- [159ace5](https://github.com/kubestash/kubestash/commit/159ace5) Add addon APIs
- [707d016](https://github.com/kubestash/kubestash/commit/707d016) Add API types
- [c690e09](https://github.com/kubestash/kubestash/commit/c690e09) Rename `backup`,`restore`, and `template` API groups into `core`
- [055a06e](https://github.com/kubestash/kubestash/commit/055a06e) Replace Apache License with AppsCode License
- [33db30b](https://github.com/kubestash/kubestash/commit/33db30b) Add BackupBlueprint and HookTemplate in core API group
- [8e3a54c](https://github.com/kubestash/kubestash/commit/8e3a54c) Rename `backup`,`restore` API groups into `core`
- [210ef3f](https://github.com/kubestash/kubestash/commit/210ef3f) Groups similar API resources into different groups
- [9f21eb3](https://github.com/kubestash/kubestash/commit/9f21eb3) Bootstrap initial APIs



