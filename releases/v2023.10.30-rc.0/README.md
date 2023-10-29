# KubeStash v2023.10.30-rc.0 (2023-10-29)


## [kubestash/apimachinery](https://github.com/kubestash/apimachinery)

### [v0.2.0-rc.0](https://github.com/kubestash/apimachinery/releases/tag/v0.2.0-rc.0)

- [340561a](https://github.com/kubestash/apimachinery/commit/340561a) Update storage reference type (#63)
- [bfdb816](https://github.com/kubestash/apimachinery/commit/bfdb816) Add constant for db version env (#65)
- [67092cd](https://github.com/kubestash/apimachinery/commit/67092cd) Update deps
- [410b43b](https://github.com/kubestash/apimachinery/commit/410b43b) Return error from dump (#62)
- [083046e](https://github.com/kubestash/apimachinery/commit/083046e) Add HostPath on volumeSnapshotter stats (#61)
- [1a047b4](https://github.com/kubestash/apimachinery/commit/1a047b4) Add snapshot helper method to get component path (#59)
- [4ae6a0b](https://github.com/kubestash/apimachinery/commit/4ae6a0b) Add temp empty dir const (#58)
- [be155ed](https://github.com/kubestash/apimachinery/commit/be155ed) Add local network volume (#54)
- [76aa9a9](https://github.com/kubestash/apimachinery/commit/76aa9a9) Add support for credential-less backup and restore (#49)
- [15eae58](https://github.com/kubestash/apimachinery/commit/15eae58) Update VolumeSnapshotterStats field (#47)
- [8571043](https://github.com/kubestash/apimachinery/commit/8571043) Add runtimeSettings for initializer and cleaner jobs (#52)
- [b502297](https://github.com/kubestash/apimachinery/commit/b502297) Export MaxConnections field of SetupOptions (#53)
- [dbb3201](https://github.com/kubestash/apimachinery/commit/dbb3201) Add interim volume constant (#51)
- [8970e83](https://github.com/kubestash/apimachinery/commit/8970e83) Remove unused flag variables (#48)
- [55275ca](https://github.com/kubestash/apimachinery/commit/55275ca) Add PVC constant (#45)
- [c710c2f](https://github.com/kubestash/apimachinery/commit/c710c2f) Add selector validation for pod type hook executor (#46)
- [2da68a2](https://github.com/kubestash/apimachinery/commit/2da68a2) Add HookTemplate webhook (#40)
- [794814d](https://github.com/kubestash/apimachinery/commit/794814d) Update offshoot labels + Fix Snapshot phase calculation
- [9af4139](https://github.com/kubestash/apimachinery/commit/9af4139) Replace `map[string]*runtime.RawExtension` with `*runtime.RawExtension` (#43)
- [6c579f7](https://github.com/kubestash/apimachinery/commit/6c579f7) Add singleton field in Addon (#42)
- [58603fa](https://github.com/kubestash/apimachinery/commit/58603fa) Add constant for trigger prefix (#41)
- [30eabd2](https://github.com/kubestash/apimachinery/commit/30eabd2) Remove unused const (#39)
- [5b69bc7](https://github.com/kubestash/apimachinery/commit/5b69bc7) Set total components for Backup and Restore (#34)
- [08f2608](https://github.com/kubestash/apimachinery/commit/08f2608) Fix Addon volume information (#35)
- [8e6c441](https://github.com/kubestash/apimachinery/commit/8e6c441) Add task name variable (#38)
- [00bd87d](https://github.com/kubestash/apimachinery/commit/00bd87d) Aadd helper method to check local provider (#33)
- [b051da5](https://github.com/kubestash/apimachinery/commit/b051da5) Add constants for backend offshoot labels (#31)
- [594f389](https://github.com/kubestash/apimachinery/commit/594f389) Add backupConfigurationTemplate in backupBlueprint (#30)
- [68fcb72](https://github.com/kubestash/apimachinery/commit/68fcb72) Add offshoot labels for BackupStorage (#29)
- [9afd31b](https://github.com/kubestash/apimachinery/commit/9afd31b) Update offshoot labels (#27)
- [77222ca](https://github.com/kubestash/apimachinery/commit/77222ca) Add helper method for BackupSession (#28)
- [121eb73](https://github.com/kubestash/apimachinery/commit/121eb73) Updated phase calculation for backupsession (#26)
- [e43043f](https://github.com/kubestash/apimachinery/commit/e43043f) Update restic repository for local storage (#22)
- [05caf64](https://github.com/kubestash/apimachinery/commit/05caf64) Updated snapshot conditions (#25)
- [9fd0cc1](https://github.com/kubestash/apimachinery/commit/9fd0cc1) Cleanup restic package (#20)
- [9bcf7b3](https://github.com/kubestash/apimachinery/commit/9bcf7b3) Add usage policy methods in blueprint (#24)
- [be4972e](https://github.com/kubestash/apimachinery/commit/be4972e) Fix constant for blueprint (#23)
- [288953c](https://github.com/kubestash/apimachinery/commit/288953c) Add backupBlueprint webhook (#21)
- [6c6a4fe](https://github.com/kubestash/apimachinery/commit/6c6a4fe) Shorten snapshot name (#19)
- [4b39372](https://github.com/kubestash/apimachinery/commit/4b39372) Add validator webhook for restoresession (#18)
- [d4fe687](https://github.com/kubestash/apimachinery/commit/d4fe687) Add repository in data source of restoresession (#17)
- [e355ac5](https://github.com/kubestash/apimachinery/commit/e355ac5) Add volumeClaimTemplates in target volumes (#16)
- [61facde](https://github.com/kubestash/apimachinery/commit/61facde) Add repository size and integrity in snapshot component (#15)
- [b24dbad](https://github.com/kubestash/apimachinery/commit/b24dbad) Fix resource found pointer issue (#14)
- [9be10a3](https://github.com/kubestash/apimachinery/commit/9be10a3) Add condition for backend secret existence (#11)
- [c3c22f1](https://github.com/kubestash/apimachinery/commit/c3c22f1) Remove snapshot condition (#13)
- [f11d519](https://github.com/kubestash/apimachinery/commit/f11d519) Update snapshot helper (#12)
- [466be61](https://github.com/kubestash/apimachinery/commit/466be61) Update snapshot condition (#10)
- [3352303](https://github.com/kubestash/apimachinery/commit/3352303) Add components to snapshot status (#9)
- [dbea414](https://github.com/kubestash/apimachinery/commit/dbea414) Add merge strategy markers (#8)
- [51ec9b4](https://github.com/kubestash/apimachinery/commit/51ec9b4) Add option for issuerRef in RestoreSession (#7)
- [02f0030](https://github.com/kubestash/apimachinery/commit/02f0030) Join the component directory with the restic repository path (#6)
- [8c620a0](https://github.com/kubestash/apimachinery/commit/8c620a0) Updated snapshot API (#5)
- [9eb28ca](https://github.com/kubestash/apimachinery/commit/9eb28ca) Remove release.yml



## [kubestash/cli](https://github.com/kubestash/cli)

### [v0.1.0-rc.0](https://github.com/kubestash/cli/releases/tag/v0.1.0-rc.0)




## [kubestash/elasticsearch](https://github.com/kubestash/elasticsearch)

### [v0.1.0-rc.0](https://github.com/kubestash/elasticsearch/releases/tag/v0.1.0-rc.0)

- [b9686b7](https://github.com/kubestash/elasticsearch/commit/b9686b7) Prepare for release v0.1.0-rc.0 (#3)



## [kubestash/kubedump](https://github.com/kubestash/kubedump)

### [v0.1.0-rc.0](https://github.com/kubestash/kubedump/releases/tag/v0.1.0-rc.0)

- [72bd51d](https://github.com/kubestash/kubedump/commit/72bd51d) Prepare for release v0.1.0-rc.0 (#3)
- [986715c](https://github.com/kubestash/kubedump/commit/986715c) Use Go 1.21 and firecraker runner



## [kubestash/mysql](https://github.com/kubestash/mysql)

### [v0.1.0-rc.0](https://github.com/kubestash/mysql/releases/tag/v0.1.0-rc.0)

- [f0abd94](https://github.com/kubestash/mysql/commit/f0abd94) Prepare for release v0.1.0-rc.0 (#7)



## [kubestash/postgres](https://github.com/kubestash/postgres)

### [v0.1.0-rc.0](https://github.com/kubestash/postgres/releases/tag/v0.1.0-rc.0)

- [7c55105](https://github.com/kubestash/postgres/commit/7c55105) Prepare for release v0.1.0-rc.0 (#1)
- [19eff67](https://github.com/kubestash/postgres/commit/19eff67) Use gh runner token to publish docker image
- [6a71410](https://github.com/kubestash/postgres/commit/6a71410) Use firecracker runner
- [e278d71](https://github.com/kubestash/postgres/commit/e278d71) Use Go 1.21
- [4899879](https://github.com/kubestash/postgres/commit/4899879) Update readme + cleanup



## [kubestash/pvc](https://github.com/kubestash/pvc)

### [v0.1.0-rc.0](https://github.com/kubestash/pvc/releases/tag/v0.1.0-rc.0)

- [b7ce8a7](https://github.com/kubestash/pvc/commit/b7ce8a7) Prepare for release v0.1.0-rc.0 (#8)
- [ac48a5d](https://github.com/kubestash/pvc/commit/ac48a5d) Update Dockerfile (#7)
- [650046e](https://github.com/kubestash/pvc/commit/650046e) Refactor with update addon changes (#6)
- [57c53cb](https://github.com/kubestash/pvc/commit/57c53cb) Use gh runner token to publish image
- [47ba57d](https://github.com/kubestash/pvc/commit/47ba57d) Use firecracker runner
- [4025d8f](https://github.com/kubestash/pvc/commit/4025d8f) Use Go 1.21
- [cd5dfcc](https://github.com/kubestash/pvc/commit/cd5dfcc) Set snapshot time after snapshot completed (#3)
- [4f7ec84](https://github.com/kubestash/pvc/commit/4f7ec84) Add support for PVC backup and restore (#2)
- [8fef9ea](https://github.com/kubestash/pvc/commit/8fef9ea) Update readme



## [kubestash/redis](https://github.com/kubestash/redis)

### [v0.1.0-rc.0](https://github.com/kubestash/redis/releases/tag/v0.1.0-rc.0)

- [44ac2c7](https://github.com/kubestash/redis/commit/44ac2c7) Prepare for release v0.1.0-rc.0 (#4)



## [kubestash/volume-snapshotter](https://github.com/kubestash/volume-snapshotter)

### [v0.1.0-rc.0](https://github.com/kubestash/volume-snapshotter/releases/tag/v0.1.0-rc.0)

- [07dc2770](https://github.com/kubestash/volume-snapshotter/commit/07dc2770) Prepare for release v0.1.0-rc.0 (#6)
- [d6639382](https://github.com/kubestash/volume-snapshotter/commit/d6639382) Use Go 1.21 and firecracker runner
- [f69f61ab](https://github.com/kubestash/volume-snapshotter/commit/f69f61ab) Add HostPath on volumeSnapshotter stats (#4)
- [7f07a810](https://github.com/kubestash/volume-snapshotter/commit/7f07a810)  Add concurrency to verify PVC readiness (#3)
- [9fcca853](https://github.com/kubestash/volume-snapshotter/commit/9fcca853) Merge pull request #1 from kubestash/volume-snapshotter
- [5bd6157e](https://github.com/kubestash/volume-snapshotter/commit/5bd6157e) Cleanup Signed-off-by: hmsayem <hmsayem@appscode.com>
- [7f0811fd](https://github.com/kubestash/volume-snapshotter/commit/7f0811fd) refactor code and resolve review changes Signed-off-by: Anisur Rahman <anisur@appscode.com>
- [94078d23](https://github.com/kubestash/volume-snapshotter/commit/94078d23) refactor components status Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [6bd2da11](https://github.com/kubestash/volume-snapshotter/commit/6bd2da11) seperate component-status Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [4abb3d74](https://github.com/kubestash/volume-snapshotter/commit/4abb3d74) remove restic info from dockerfile and makefile Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [8ab78c29](https://github.com/kubestash/volume-snapshotter/commit/8ab78c29) add restoretask in flag Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [fb4d2121](https://github.com/kubestash/volume-snapshotter/commit/fb4d2121) Refactor code Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [d58832bf](https://github.com/kubestash/volume-snapshotter/commit/d58832bf) remove kmapi vs_client Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [15791f43](https://github.com/kubestash/volume-snapshotter/commit/15791f43) add git-ignore Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [45c3b206](https://github.com/kubestash/volume-snapshotter/commit/45c3b206) refactor Code Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>
- [0fbba02f](https://github.com/kubestash/volume-snapshotter/commit/0fbba02f) implement restore
- [3e1ef1bc](https://github.com/kubestash/volume-snapshotter/commit/3e1ef1bc) implement backup Signed-off-by: anisurrahman75 <sunny.cse7575@gmail.com>



