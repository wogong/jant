---
id: "pst_01kxcrbczrfqa9xztytbb4nzgc"
date: "2026-07-13T03:29:22.000Z"
slug: "rwask"
type: "post"
build:
  render: "never"
  list: "local"
format: "note"
status: "published"
visibility: "public"
summary_text: "Devil's in the details : 我第一次震惊于 details 的重要性, 是恺明向我展示 ResNet 的 loss curve 要怎么 smoothing. 在合理的 median-smoothing 下, 我们能看到以 epoch 为周期的 overfitting 现象, 在多年后被其他人称为 epochal sawtooth phenomenon : 每个 epoch 的 train loss 会缓慢上升, 再在下一个 epoch 开头骤然下降."
---

**Devil's in the details**: 我第一次震惊于 details 的重要性, 是恺明向我展示 ResNet 的 loss curve 要怎么 smoothing. 在合理的 median-smoothing 下, 我们能看到以 epoch 为周期的 overfitting 现象, 在多年后被其他人称为 [epochal sawtooth phenomenon](https://arxiv.org/pdf/2410.10056v3): 每个 epoch 的 train loss 会缓慢上升, 再在下一个 epoch 开头骤然下降.
