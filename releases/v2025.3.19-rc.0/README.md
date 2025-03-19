# KubeStash v2025.3.19-rc.0 (2025-03-19)


## [kubestash/apimachinery](https://github.com/kubestash/apimachinery)

### [v0.17.0-rc.0](https://github.com/kubestash/apimachinery/releases/tag/v0.17.0-rc.0)

- [0e805914](https://github.com/kubestash/apimachinery/commit/0e805914) Update deps
- [aefab6a6](https://github.com/kubestash/apimachinery/commit/aefab6a6) Update controller config
- [aa10be69](https://github.com/kubestash/apimachinery/commit/aa10be69) Add IRSA annotation utility (#161)
- [5fc5e168](https://github.com/kubestash/apimachinery/commit/5fc5e168) Skip extracting restic output lines if `message_type` is not summary
- [74531c6c](https://github.com/kubestash/apimachinery/commit/74531c6c) Merge pull request #159 from kubestash/v3
- [7a5e5c63](https://github.com/kubestash/apimachinery/commit/7a5e5c63) incorporate cahnges with one struct
- [d928d133](https://github.com/kubestash/apimachinery/commit/d928d133) set region for S3-IRSA
- [d11830db](https://github.com/kubestash/apimachinery/commit/d11830db) change webhooks directory
- [ff90d99c](https://github.com/kubestash/apimachinery/commit/ff90d99c) Fix v3 webhook signature for BackupStorage
- [2ecbedaa](https://github.com/kubestash/apimachinery/commit/2ecbedaa) Use k8s 1.32 client libs
- [1bebb656](https://github.com/kubestash/apimachinery/commit/1bebb656) Use Go 1.24 (#157)
- [57156d93](https://github.com/kubestash/apimachinery/commit/57156d93) Update deps
- [1a6fe49b](https://github.com/kubestash/apimachinery/commit/1a6fe49b) fix s3-compitbale storage endpoint resolver (#156)
- [f1e579e0](https://github.com/kubestash/apimachinery/commit/f1e579e0) Disable image caching in setup-qemu action (#155)



## [kubestash/kubestash](https://github.com/kubestash/kubestash)

### [v0.17.0-rc.0](https://github.com/kubestash/kubestash/releases/tag/v0.17.0-rc.0)

- [4da9a4a5](https://github.com/kubestash/kubestash/commit/4da9a4a5) Prepare for release v0.17.0-rc.0 (#288)
- [e4da511f](https://github.com/kubestash/kubestash/commit/e4da511f) Add irsa role annotation to every executor SA (#285)
- [9dfa0ae3](https://github.com/kubestash/kubestash/commit/9dfa0ae3) Remove rabcproxy sidecar (#287)
- [499b0bec](https://github.com/kubestash/kubestash/commit/499b0bec) Use restic 0.17.3 (#286)
- [f3b84de4](https://github.com/kubestash/kubestash/commit/f3b84de4) Merge pull request #284 from kubestash/v3
- [177eeda8](https://github.com/kubestash/kubestash/commit/177eeda8) update deps
- [4e993db0](https://github.com/kubestash/kubestash/commit/4e993db0) update apimachinery Signed-off-by: Anisur Rahman <anisur@appscode.com>
- [e75220d8](https://github.com/kubestash/kubestash/commit/e75220d8) Re-import `SetupWebhookWithManager` from webhook cmd
- [8414822c](https://github.com/kubestash/kubestash/commit/8414822c) Use Go 1.24 (#282)
- [bf782c59](https://github.com/kubestash/kubestash/commit/bf782c59) Use Go 1.24 (#281)
- [0972e4cc](https://github.com/kubestash/kubestash/commit/0972e4cc) Fix restore executor nil reference check for `archiverRef` (#280)
- [f55d932d](https://github.com/kubestash/kubestash/commit/f55d932d) Prepare for release v0.16.0 (#278)



