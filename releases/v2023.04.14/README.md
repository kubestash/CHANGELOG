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



