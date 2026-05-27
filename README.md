# tgoskits VirtIO 技术总结

本仓库用于公开整理我在 `rcore-os/tgoskits` 上完成的 `ArceOS VirtIO` 相关贡献材料。

- 上游仓库：<https://github.com/rcore-os/tgoskits>
- 对应 PR：<https://github.com/rcore-os/tgoskits/pull/376>
- PR 标题：`增强 ArceOS 中 VirtIO Net、Vsock 及通用探测路径`
- 合并状态：已合并
- merge commit：`90dd789fb4a4624d1fc923f73f94ffcd409059fa`

本次工作主要围绕：

- `virtio-net` 的队列记账、buffer 生命周期与异常路径安全
- `virtio-vsock` 的协议语义、参数校验与事件路径
- `VirtIO` 公共 `probe / glue / HAL / PCI IRQ` 分层整理

详细说明见：

- [工作说明.md](工作说明.md)
