# KubeStash v2023.11.28-rc.1 (2023-11-28)


## [kubestash/apimachinery](https://github.com/kubestash/apimachinery)

### [v0.2.0-rc.1](https://github.com/kubestash/apimachinery/releases/tag/v0.2.0-rc.1)

- [f782c9a](https://github.com/kubestash/apimachinery/commit/f782c9a) Add snapshot labels for listing snapshots with label selector (#78)
- [9ac07ef](https://github.com/kubestash/apimachinery/commit/9ac07ef) Add constant for snapshot version (#79)
- [1593f57](https://github.com/kubestash/apimachinery/commit/1593f57) Add helper method for calculating backup data size (#77)
- [0b99d5c](https://github.com/kubestash/apimachinery/commit/0b99d5c) Update webhooks (#72)
- [329d29d](https://github.com/kubestash/apimachinery/commit/329d29d) Update RestoreSession webhook for PITR (#64)
- [1f77f29](https://github.com/kubestash/apimachinery/commit/1f77f29) Add missing volume populator const (#76)
- [ec33cf6](https://github.com/kubestash/apimachinery/commit/ec33cf6) Update temp volume consts (#73)
- [690b178](https://github.com/kubestash/apimachinery/commit/690b178) Add const for volume populator (#55)
- [5907022](https://github.com/kubestash/apimachinery/commit/5907022) Use reflector for comparing BackupStorage (#71)
- [f213641](https://github.com/kubestash/apimachinery/commit/f213641) Add update-crds workflow
- [0e446d8](https://github.com/kubestash/apimachinery/commit/0e446d8) Revise empty check for restic host (#69)
- [086480c](https://github.com/kubestash/apimachinery/commit/086480c) Add restic methods for managing restic keys (#60)
- [629491e](https://github.com/kubestash/apimachinery/commit/629491e) Add backupstorage webhook (#66)
- [967f313](https://github.com/kubestash/apimachinery/commit/967f313) Add constants for kubedump (#50)
- [407f425](https://github.com/kubestash/apimachinery/commit/407f425) Add session name to BackupSession offshoot labels (#67)



## [kubestash/cli](https://github.com/kubestash/cli)

### [v0.1.0-rc.1](https://github.com/kubestash/cli/releases/tag/v0.1.0-rc.1)

- [e9c82ca](https://github.com/kubestash/cli/commit/e9c82ca) Prepare for release v0.1.0-rc.1 (#6)
- [d7f30d0](https://github.com/kubestash/cli/commit/d7f30d0) Update deps (#5)
- [bff2dff](https://github.com/kubestash/cli/commit/bff2dff) Refactor + Revendor (#4)
- [ace4173](https://github.com/kubestash/cli/commit/ace4173) Implement kubestash CLI (#1)



## [kubestash/installer](https://github.com/kubestash/installer)

### [v2023.11.28-rc.1](https://github.com/kubestash/installer/releases/tag/v2023.11.28-rc.1)

- [5e15f5d](https://github.com/kubestash/installer/commit/5e15f5d) Prepare for release v2023.11.28-rc.1 (#37)
- [791d11f](https://github.com/kubestash/installer/commit/791d11f) Removed unnecessary permissions (#35)
- [cc88b7f](https://github.com/kubestash/installer/commit/cc88b7f) Rename volumeSnapshotClassName flag and function name (#36)
- [08fc0aa](https://github.com/kubestash/installer/commit/08fc0aa) Add necessary RBAC permission for mongodb and mysql (#31)
- [160d8ce](https://github.com/kubestash/installer/commit/160d8ce) Check for image existence (#33)
- [bdbaba5](https://github.com/kubestash/installer/commit/bdbaba5) Move db addons to kubedb project (#32)
- [4a4f5f2](https://github.com/kubestash/installer/commit/4a4f5f2) Add RBAC permission for elasticsearch (#29)
- [55bf292](https://github.com/kubestash/installer/commit/55bf292) Add mutating webhook for BackupConfiguration (#30)
- [64a99a8](https://github.com/kubestash/installer/commit/64a99a8) Fix operator configuration for registry (#28)
- [6672093](https://github.com/kubestash/installer/commit/6672093) Fix permissions for ensuring AppBinding crd (#27)
- [6a31709](https://github.com/kubestash/installer/commit/6a31709) Add permissions for ensuring AppBinding crd (#26)
- [42d9c19](https://github.com/kubestash/installer/commit/42d9c19) Update PVC addon + operator RBAC permission (#24)
- [c2e33ea](https://github.com/kubestash/installer/commit/c2e33ea) Move VolumeSnapshot and manifest addon tasks to their respective addon (#25)
- [e9c78da](https://github.com/kubestash/installer/commit/e9c78da) Add PVC addon (#23)
- [8ad56e9](https://github.com/kubestash/installer/commit/8ad56e9) Update temp volume name and mount path (#22)
- [901a9fa](https://github.com/kubestash/installer/commit/901a9fa) Update tmp volume name (#21)
- [1c01b42](https://github.com/kubestash/installer/commit/1c01b42) Update scratchDir on catalog addons (#20)
- [d228c29](https://github.com/kubestash/installer/commit/d228c29) Remove stash function and task crds (#19)
- [4009561](https://github.com/kubestash/installer/commit/4009561) Add catalog chart (#16)



## [kubestash/kubedump](https://github.com/kubestash/kubedump)

### [v0.1.0-rc.1](https://github.com/kubestash/kubedump/releases/tag/v0.1.0-rc.1)

- [7761f2c](https://github.com/kubestash/kubedump/commit/7761f2c) Prepare for release v0.1.0-rc.1 (#6)
- [efff060](https://github.com/kubestash/kubedump/commit/efff060) Update snapshot time (#5)



## [kubestash/kubestash](https://github.com/kubestash/kubestash)

### [v0.2.0-rc.1](https://github.com/kubestash/kubestash/releases/tag/v0.2.0-rc.1)

- [7b6bce51](https://github.com/kubestash/kubestash/commit/7b6bce51) Prepare for release v0.2.0-rc.1 (#166)
- [a3f36cff](https://github.com/kubestash/kubestash/commit/a3f36cff) Check target kind before resolving image version
- [aaa8766a](https://github.com/kubestash/kubestash/commit/aaa8766a) Use AppBinding version to resolve function image version (#165)
- [a057a486](https://github.com/kubestash/kubestash/commit/a057a486) Add snapshot labels for listing snapshots with label selector (#162)
- [ba899bed](https://github.com/kubestash/kubestash/commit/ba899bed) Resolve function image version for database addons (#159)
- [50e190a9](https://github.com/kubestash/kubestash/commit/50e190a9) Fix snapshot ID + Set snapshot version (#163)
- [6d1c181a](https://github.com/kubestash/kubestash/commit/6d1c181a) Calculate storage request for interim volume of elasticsearch (#156)
- [de07e948](https://github.com/kubestash/kubestash/commit/de07e948) Cleanup pending snapshots when BackupSession is deleted (#160)
- [1df4bec6](https://github.com/kubestash/kubestash/commit/1df4bec6) Update deps (#158)
- [61303ffc](https://github.com/kubestash/kubestash/commit/61303ffc) Fix make install cmd (#157)
- [d584ed67](https://github.com/kubestash/kubestash/commit/d584ed67) Ensure AppBinding CRD (#154)
- [3d74c43c](https://github.com/kubestash/kubestash/commit/3d74c43c) Fix backup blueprint deletion action (#155)
- [a1e2cce2](https://github.com/kubestash/kubestash/commit/a1e2cce2) Add support for Point-In-Time Recovery (PITR) (#151)
- [c36e50a6](https://github.com/kubestash/kubestash/commit/c36e50a6) Add local network volume accessor (#147)
- [b511fde6](https://github.com/kubestash/kubestash/commit/b511fde6) Add Support for PVC Volume populator (#149)
- [c3ed7822](https://github.com/kubestash/kubestash/commit/c3ed7822) Add support for kubernetes resources backup and restore (#145)



## [kubestash/pvc](https://github.com/kubestash/pvc)

### [v0.1.0-rc.1](https://github.com/kubestash/pvc/releases/tag/v0.1.0-rc.1)

- [a86ddab](https://github.com/kubestash/pvc/commit/a86ddab) Prepare for release v0.1.0-rc.1 (#13)
- [d11f9e4](https://github.com/kubestash/pvc/commit/d11f9e4) Update snapshot time (#12)
- [7a84bed](https://github.com/kubestash/pvc/commit/7a84bed) Add exclude flag for backup (#11)
- [f163d02](https://github.com/kubestash/pvc/commit/f163d02) Update deps (#10)
- [0db3f68](https://github.com/kubestash/pvc/commit/0db3f68) Switch to function from method for updating snapshot component status (#9)



## [kubestash/volume-snapshotter](https://github.com/kubestash/volume-snapshotter)

### [v0.1.0-rc.1](https://github.com/kubestash/volume-snapshotter/releases/tag/v0.1.0-rc.1)

- [ec0eb085](https://github.com/kubestash/volume-snapshotter/commit/ec0eb085) Prepare for release v0.1.0-rc.1 (#10)
- [3c092abc](https://github.com/kubestash/volume-snapshotter/commit/3c092abc) Update snapshot time (#9)
- [b6dfca6f](https://github.com/kubestash/volume-snapshotter/commit/b6dfca6f) Update deps (#8)
- [ab8f8eae](https://github.com/kubestash/volume-snapshotter/commit/ab8f8eae) Use default VolumeSnapshotClass if it is empty (#7)



## [kubestash/workload](https://github.com/kubestash/workload)

### [v0.1.0-rc.1](https://github.com/kubestash/workload/releases/tag/v0.1.0-rc.1)

- [4c6c945](https://github.com/kubestash/workload/commit/4c6c945) Prepare for release v0.1.0-rc.1 (#25)
- [9318bb5](https://github.com/kubestash/workload/commit/9318bb5) Remove unnecessary method receiver (#24)
- [58eb7cf](https://github.com/kubestash/workload/commit/58eb7cf) Fix snapshot time (#23)
- [c76d6a8](https://github.com/kubestash/workload/commit/c76d6a8) Update deps (#22)



