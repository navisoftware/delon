---
order: 10
title: 常见问题
type: Documents
---

## 为什么can方法默认情况下角色是字符串，而权限点是数字类型？

我们无法区分在同一个字符串类型的情况下如何自动区分角色还是权限点，源于此作了这样的设计。因此对于角色使用字符串、权限点使用数字型的后端设计编码体验会更好，你无须再使用 `canAbility` 来表达权限点或使用 `ACLType` 复杂类型表述。
