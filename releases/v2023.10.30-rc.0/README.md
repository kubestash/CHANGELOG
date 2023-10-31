# KubeStash v2023.10.30-rc.0 (2023-10-31)


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



## [kubestash/installer](https://github.com/kubestash/installer)

### [v2023.10.30-rc.0](https://github.com/kubestash/installer/releases/tag/v2023.10.30-rc.0)

- [0fead13](https://github.com/kubestash/installer/commit/0fead13) Prepare for release v2023.10.30-rc.0 (#14)
- [db149d7](https://github.com/kubestash/installer/commit/db149d7) Import crds without description
- [36291d8](https://github.com/kubestash/installer/commit/36291d8) Import crds
- [be1e6be](https://github.com/kubestash/installer/commit/be1e6be) Add permissions for storageclasses (#13)
- [764ce03](https://github.com/kubestash/installer/commit/764ce03) Update deps
- [49b943b](https://github.com/kubestash/installer/commit/49b943b) Give volume snapshotter necessary rbac (#12)
- [c498b57](https://github.com/kubestash/installer/commit/c498b57) Add support for local network volume (#10)



## [kubestash/kubedb-manifest](https://github.com/kubestash/kubedb-manifest)

### [v0.2.0-rc.0](https://github.com/kubestash/kubedb-manifest/releases/tag/v0.2.0-rc.0)

- [35c6b95](https://github.com/kubestash/kubedb-manifest/commit/35c6b95) Prepare for release v0.2.0-rc.0 (#22)
- [da97d9a](https://github.com/kubestash/kubedb-manifest/commit/da97d9a) Use gh runner token to publish image
- [592c51f](https://github.com/kubestash/kubedb-manifest/commit/592c51f) Use firecracker runner
- [008042d](https://github.com/kubestash/kubedb-manifest/commit/008042d) Use Go 1.21
- [985bcab](https://github.com/kubestash/kubedb-manifest/commit/985bcab) Set snapshot time after snapshot completed (#21)
- [6a8c682](https://github.com/kubestash/kubedb-manifest/commit/6a8c682) Refactor code (#20)
- [bcb944d](https://github.com/kubestash/kubedb-manifest/commit/bcb944d) Remove manifest option flags (#19)
- [5a47722](https://github.com/kubestash/kubedb-manifest/commit/5a47722) Fix secret restore issue (#18)
- [3ced8b7](https://github.com/kubestash/kubedb-manifest/commit/3ced8b7) Update `kmodules.xyz/client-go` version to `v0.25.27` (#17)
- [2ee1314](https://github.com/kubestash/kubedb-manifest/commit/2ee1314) Update Readme (#16)
- [42d0e52](https://github.com/kubestash/kubedb-manifest/commit/42d0e52) Set initial component status prior to backup and restore (#15)
- [31a64d6](https://github.com/kubestash/kubedb-manifest/commit/31a64d6) Remove redundant flags (#14)
- [a804ba8](https://github.com/kubestash/kubedb-manifest/commit/a804ba8) Pass Snapshot name for restore
- [99ca49f](https://github.com/kubestash/kubedb-manifest/commit/99ca49f) Set snapshot time, integrity and size (#12)
- [384bbb6](https://github.com/kubestash/kubedb-manifest/commit/384bbb6) Set backup error in component status + Refactor codebase (#11)
- [513eef5](https://github.com/kubestash/kubedb-manifest/commit/513eef5) Update for snapshot and restoresession API changes (#10)
- [4fb8f52](https://github.com/kubestash/kubedb-manifest/commit/4fb8f52) Add options for issuerref (#9)
- [2931d9e](https://github.com/kubestash/kubedb-manifest/commit/2931d9e) Update restic modules (#7)
- [3422ddf](https://github.com/kubestash/kubedb-manifest/commit/3422ddf) Fix bugs + Sync with updated snapshot api (#6)



## [kubestash/kubedump](https://github.com/kubestash/kubedump)

### [v0.1.0-rc.0](https://github.com/kubestash/kubedump/releases/tag/v0.1.0-rc.0)

- [72bd51d](https://github.com/kubestash/kubedump/commit/72bd51d) Prepare for release v0.1.0-rc.0 (#3)
- [986715c](https://github.com/kubestash/kubedump/commit/986715c) Use Go 1.21 and firecraker runner



## [kubestash/kubestash](https://github.com/kubestash/kubestash)

### [v0.2.0-rc.0](https://github.com/kubestash/kubestash/releases/tag/v0.2.0-rc.0)

- [50f06ffb](https://github.com/kubestash/kubestash/commit/50f06ffb) Prepare for release v0.2.0-rc.0 (#152)
- [41cce3d9](https://github.com/kubestash/kubestash/commit/41cce3d9) Update storage reference type + Set repo storage reference to current BackupStorage (#150)
- [354b3b8c](https://github.com/kubestash/kubestash/commit/354b3b8c) Use firecracker runner and Go 1.21
- [633ab4cf](https://github.com/kubestash/kubestash/commit/633ab4cf) Add support for credential-less backup and restore (#143)
- [60b06f0a](https://github.com/kubestash/kubestash/commit/60b06f0a) Add support for volume-snapshots (#136)
- [f2639ce7](https://github.com/kubestash/kubestash/commit/f2639ce7) Fix empty restic data snapshot deletion (#148)
- [9d60189c](https://github.com/kubestash/kubestash/commit/9d60189c) Fix addon interim volume data dir (#146)
- [6de5b73b](https://github.com/kubestash/kubestash/commit/6de5b73b) Fix backupstorage reconcile issue for watching resources (#144)
- [7c8771bf](https://github.com/kubestash/kubestash/commit/7c8771bf) Fix pause BackupConfig after applying RestoreSession (#142)
- [7637680e](https://github.com/kubestash/kubestash/commit/7637680e) Fix excessive requeue logs for backupstorage (#139)
- [b4aad66d](https://github.com/kubestash/kubestash/commit/b4aad66d) Update addon flags var (#140)
- [a8c3a1f0](https://github.com/kubestash/kubestash/commit/a8c3a1f0) Add support for PVC auto backup (#138)
- [a5f3d7a9](https://github.com/kubestash/kubestash/commit/a5f3d7a9) Fix recent snapshot list not updating accurately issue (#137)
- [0711a13a](https://github.com/kubestash/kubestash/commit/0711a13a) Add version cmd (#135)
- [02bd9477](https://github.com/kubestash/kubestash/commit/02bd9477) Fix repoinfo in backupstorage (#134)
- [3670a2e8](https://github.com/kubestash/kubestash/commit/3670a2e8) Fix restore job cleanup issue (#133)
- [68885c99](https://github.com/kubestash/kubestash/commit/68885c99) Add appbinding `get` permission in restore role (#132)
- [4ee56ed6](https://github.com/kubestash/kubestash/commit/4ee56ed6) Trigger the next retention policy in case of failure (#131)
- [afcf1251](https://github.com/kubestash/kubestash/commit/afcf1251) Always update retention policy status (#130)
- [b9840a08](https://github.com/kubestash/kubestash/commit/b9840a08) Add support for PVC backup and restore (#128)
- [ccdc8741](https://github.com/kubestash/kubestash/commit/ccdc8741) Add support for hook template (#115)
- [61c2c19a](https://github.com/kubestash/kubestash/commit/61c2c19a) Remove manifest options flag variables (#126)
- [bc25d891](https://github.com/kubestash/kubestash/commit/bc25d891) Apply retention-policy from backup Job (#121)
- [ec993c59](https://github.com/kubestash/kubestash/commit/ec993c59) Implement backend resource cleanup executor (#122)
- [1960587f](https://github.com/kubestash/kubestash/commit/1960587f) Resolve function args for addon parameters (#125)
- [f68e6d50](https://github.com/kubestash/kubestash/commit/f68e6d50) Fix latest snapshot calculation (#124)
- [54a546c9](https://github.com/kubestash/kubestash/commit/54a546c9) Resolve addon params (#123)
- [c4a20ea1](https://github.com/kubestash/kubestash/commit/c4a20ea1) Set total components using singleton specifier (#118)
- [61590286](https://github.com/kubestash/kubestash/commit/61590286) Skip applying retention policy if not found. (#117)
- [5d4e01f9](https://github.com/kubestash/kubestash/commit/5d4e01f9) Fix Cronjob name generation (#116)
- [4ea589b9](https://github.com/kubestash/kubestash/commit/4ea589b9) Set total components for Backup and Restore (#109)
- [cfc78936](https://github.com/kubestash/kubestash/commit/cfc78936) Add support for addon volumes (#113)
- [6ac04f25](https://github.com/kubestash/kubestash/commit/6ac04f25) Resolve task name variable (#114)
- [3317fdf0](https://github.com/kubestash/kubestash/commit/3317fdf0) Update README (#110)
- [693e4b65](https://github.com/kubestash/kubestash/commit/693e4b65) Add support for local backend
- [a2353eb9](https://github.com/kubestash/kubestash/commit/a2353eb9) Implement auto-backup (#104)
- [d07d522e](https://github.com/kubestash/kubestash/commit/d07d522e) Refactor backend initialization (#108)
- [ca3085a7](https://github.com/kubestash/kubestash/commit/ca3085a7) Add support for cross-namespace backup and restore (#107)
- [a5c2163a](https://github.com/kubestash/kubestash/commit/a5c2163a) Fix session skipping and cleanup (#106)
- [bfc7c8eb](https://github.com/kubestash/kubestash/commit/bfc7c8eb) Refactor resolver package + Initialize backend once (#101)
- [30185cf3](https://github.com/kubestash/kubestash/commit/30185cf3) Pass backupstorages to backup and restore executor (#102)
- [2e2ec9fc](https://github.com/kubestash/kubestash/commit/2e2ec9fc) Fix backup job name (#99)
- [42c6f79d](https://github.com/kubestash/kubestash/commit/42c6f79d) Add support for latest snapshot restore (#98)
- [8dfd3f98](https://github.com/kubestash/kubestash/commit/8dfd3f98) Add volume claim template (#97)
- [18db497a](https://github.com/kubestash/kubestash/commit/18db497a) Use `blob` for backend (#90)
- [36ea681c](https://github.com/kubestash/kubestash/commit/36ea681c) Set snapshot time (#96)
- [7e16185e](https://github.com/kubestash/kubestash/commit/7e16185e) Add backup and restore logic for workload (#70)
- [b91517c5](https://github.com/kubestash/kubestash/commit/b91517c5) Add backend secret condition (#93)
- [5b2439ea](https://github.com/kubestash/kubestash/commit/5b2439ea) Add option for issuerRef in RestoreSession (#92)
- [ab353888](https://github.com/kubestash/kubestash/commit/ab353888) Update restic modules (#91)
- [458d182e](https://github.com/kubestash/kubestash/commit/458d182e) Delete all Restic snapshots for each component instead of one. (#89)
- [27d5d7ec](https://github.com/kubestash/kubestash/commit/27d5d7ec) Fix S3 directory cleanup (#88)
- [9213be05](https://github.com/kubestash/kubestash/commit/9213be05) Fix storage cleanup (#87)



## [kubestash/mongodb](https://github.com/kubestash/mongodb)

### [v0.1.0-rc.0](https://github.com/kubestash/mongodb/releases/tag/v0.1.0-rc.0)

- [d3e752d](https://github.com/kubestash/mongodb/commit/d3e752d) Prepare for release v0.1.0-rc.0 (#7)



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



## [kubestash/workload](https://github.com/kubestash/workload)

### [v0.1.0-rc.0](https://github.com/kubestash/workload/releases/tag/v0.1.0-rc.0)

- [f33596e](https://github.com/kubestash/workload/commit/f33596e) Prepare for release v0.1.0-rc.0 (#21)
- [028c967](https://github.com/kubestash/workload/commit/028c967) Add missing flags (#20)
- [e7bf1b3](https://github.com/kubestash/workload/commit/e7bf1b3) Update deps
- [43d82cc](https://github.com/kubestash/workload/commit/43d82cc) Refactor
- [429e16a](https://github.com/kubestash/workload/commit/429e16a) Remove get component path func
- [76bb516](https://github.com/kubestash/workload/commit/76bb516) Use GitHub runner token for publishing images
- [7866112](https://github.com/kubestash/workload/commit/7866112) Use firecracker runner
- [a895b83](https://github.com/kubestash/workload/commit/a895b83) Use Go 1.21
- [f69e980](https://github.com/kubestash/workload/commit/f69e980) Add support for credential-less backup and restore (#16)
- [0c1dc11](https://github.com/kubestash/workload/commit/0c1dc11) Set snapshot time after snapshot completed (#15)
- [082ef12](https://github.com/kubestash/workload/commit/082ef12) Remove taskName flag (#14)
- [faa0072](https://github.com/kubestash/workload/commit/faa0072) Pass parameters through flags (#13)
- [c4076e9](https://github.com/kubestash/workload/commit/c4076e9) Resolve addon params (#12)
- [0edba4d](https://github.com/kubestash/workload/commit/0edba4d) Add flag for task name + Refactor (#11)
- [ab41893](https://github.com/kubestash/workload/commit/ab41893) Update Readme (#10)
- [87a5a2b](https://github.com/kubestash/workload/commit/87a5a2b) Add task flag (#9)
- [6e31c77](https://github.com/kubestash/workload/commit/6e31c77) Set initial component status prior to backup (#8)
- [6f71e6e](https://github.com/kubestash/workload/commit/6f71e6e) Remove redundant flags (#7)
- [89049e5](https://github.com/kubestash/workload/commit/89049e5) Add snapshotName for restore (#6)
- [b7ba2d5](https://github.com/kubestash/workload/commit/b7ba2d5) Set snapshot time, integrity and size (#5)
- [75a9261](https://github.com/kubestash/workload/commit/75a9261) Merge pull request #2 from kubestash/workload-backup
- [7d1b0ae](https://github.com/kubestash/workload/commit/7d1b0ae) Run fmt
- [f441856](https://github.com/kubestash/workload/commit/f441856) Remove comment from constant
- [5fb15a9](https://github.com/kubestash/workload/commit/5fb15a9) Refactor code
- [6e435a3](https://github.com/kubestash/workload/commit/6e435a3) Initiate backup
- [0024b96](https://github.com/kubestash/workload/commit/0024b96) Refactor code
- [50256bf](https://github.com/kubestash/workload/commit/50256bf) Fixed snapshot condition sync issue
- [2654383](https://github.com/kubestash/workload/commit/2654383) Fix restore duration with respect to restic
- [4820508](https://github.com/kubestash/workload/commit/4820508) Fix ci yaml
- [7190934](https://github.com/kubestash/workload/commit/7190934) Fix release yaml
- [9d92e64](https://github.com/kubestash/workload/commit/9d92e64) Fix duration for restore
- [94d1ad9](https://github.com/kubestash/workload/commit/94d1ad9) Update components for new API
- [723f73a](https://github.com/kubestash/workload/commit/723f73a) Print patch
- [262c26a](https://github.com/kubestash/workload/commit/262c26a) Update snapshot status
- [2870906](https://github.com/kubestash/workload/commit/2870906) Update for daemonset executor job
- [7a21b97](https://github.com/kubestash/workload/commit/7a21b97) Fixed daemon restart issue + conflict error
- [f728b6e](https://github.com/kubestash/workload/commit/f728b6e) Fixed pathInfo pointer issue
- [5502e6a](https://github.com/kubestash/workload/commit/5502e6a) Refactored code
- [fe5d2e1](https://github.com/kubestash/workload/commit/fe5d2e1) Fixed scratchDir name + trim paths
- [ac8c538](https://github.com/kubestash/workload/commit/ac8c538) Added HostPath in ResticStats
- [eb834fe](https://github.com/kubestash/workload/commit/eb834fe) Fixed components status update
- [b6b8530](https://github.com/kubestash/workload/commit/b6b8530) Update for resticStats array field
- [eed5549](https://github.com/kubestash/workload/commit/eed5549) Fixed snapshot pointer issue
- [ffb7ec9](https://github.com/kubestash/workload/commit/ffb7ec9) Fixed snapshot components issue
- [ba68169](https://github.com/kubestash/workload/commit/ba68169) Added restore logic
- [8537ed4](https://github.com/kubestash/workload/commit/8537ed4) Refactor backup and restore path method
- [6de2585](https://github.com/kubestash/workload/commit/6de2585) Refactor code
- [559c97e](https://github.com/kubestash/workload/commit/559c97e) Implemented workload addon
- [2ccb7db](https://github.com/kubestash/workload/commit/2ccb7db) Use uid 65534 and test against K8s 1.27.0 (#4)
- [09d9b65](https://github.com/kubestash/workload/commit/09d9b65) Use ghcr.io for appscode/golang-dev (#3)
- [cb05914](https://github.com/kubestash/workload/commit/cb05914) Merge pull request #1 from kubestash/clone
- [615f53f](https://github.com/kubestash/workload/commit/615f53f) Update Readme
- [46ba516](https://github.com/kubestash/workload/commit/46ba516) Clone data from kubedb-manifest



