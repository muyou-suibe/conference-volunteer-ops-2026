# 2026 大会志愿者项目管理

> `conference-volunteer-ops-2026`

本仓库用于 **KubeCon + CloudNativeCon + OpenInfra Summit + PyTorch Conference China 2026** 志愿者项目的内部协作与执行管理。

主要覆盖：

- 成员入组
- 培训管理
- Availability 确认
- 正式排班
- 岗位分配
- 现场协作
- 签到签退
- 异常处理
- 加班确认
- 项目复盘

> 本仓库不是公开招募渠道。
>
> 招募发布、候选人筛选、内部评价以及身份证、银行卡等敏感个人信息，不在本仓库中管理。

---

## 一、项目概览

| 项目 | 信息 |
|---|---|
| 活动时间 | 2026 年 9 月 6 日至 9 月 9 日 |
| 项目管理 | 3 名负责人共同管理 |
| 正式志愿者规模 | 20 人 |
| 当前阶段 | 🟡 筹备中 |
| 管理工具 | GitHub + 即时通讯 |
| 仓库用途 | 入组、培训、排班、现场执行与复盘 |

具体活动地点、集合地点和现场联系方式，以活动前正式内部通知为准。

---

## 二、每日人员需求

| 日期 | 计划人数 |
|---|---:|
| 9 月 6 日 | 4 人 |
| 9 月 7 日 | 8 人 |
| 9 月 8 日 | 20 人 |
| 9 月 9 日 | 20 人 |

> “某天可以参加”不等于“某天已经被正式排班”。
>
> 最终安排以 `docs/03-schedule/` 中的正式排班为准。

---

## 三、项目目标

通过 GitHub 建立一套完整、可追踪、可执行的志愿者项目管理流程。

整体流程：

    正式确认参与
          ↓
    收集 GitHub Username
          ↓
    分配 Volunteer ID
          ↓
    加入项目协作空间
          ↓
    完成入组
          ↓
    完成培训
          ↓
    确认 Availability
          ↓
    确认正式排班
          ↓
    确认岗位与负责人
          ↓
    READY
          ↓
    现场执行
          ↓
    签到 / 签退 / 加班确认
          ↓
    项目复盘

最终目标：

> 在活动开始前，使所有正式成员达到可执行的 `READY` 状态。

---

## 四、项目管理原则

### 1. GitHub 是正式信息源

本项目采用：

> **GitHub = Single Source of Truth**

GitHub 用于保存正式版本的：

- 项目管理规则
- 项目负责人职责
- 志愿者准备状态
- Availability
- 培训资料
- 正式排班
- 岗位说明
- SOP
- 项目任务
- 重要变更
- 现场异常记录
- 项目复盘

即时通讯用于：

- 实时通知
- 集合提醒
- 临时协调
- 现场调度
- 紧急问题

如果即时通讯、私聊或现场口头讨论形成正式决定，应同步更新 GitHub。

---

### 2. One Task, One Owner

一项任务可以有多人协助，但必须明确一名主要负责人。

原则：

> **One Task, One Owner**

避免出现：

> “A、B、C 一起负责。”

正确方式应是：

    任务
      ↓
    明确 Owner
      ↓
    明确截止时间
      ↓
    推进执行
      ↓
    确认结果

---

### 3. Availability 与 Schedule 分离

必须严格区分：

    Availability
    = 这个人当天是否可以参加

    Schedule
    = 项目负责人是否正式安排这个人当天工作

例如：

    V005
    9 月 6 日 Availability：✅
    9 月 6 日 Schedule：未安排

这是正常情况。

---

### 4. 计划排班与实际出勤分离

正式排班回答：

> 谁应该来？

签到签退回答：

> 谁实际来了？实际工作了多久？

不能仅根据排班判断最终出勤和实际工作时间。

---

## 五、项目管理团队

本项目由三名负责人共同管理。

推荐职责结构：

| 管理角色 | 主要职责 |
|---|---|
| Project Lead / 项目统筹 | 总体进度、关键决策、跨模块协调 |
| People & Scheduling / 人员与排班 | 人员、入组、培训状态、Availability、正式排班 |
| Operations / 现场运营 | 岗位、会场、签到签退、现场调度、异常处理 |

详细职责：

[`docs/00-management/responsibilities.md`](docs/00-management/responsibilities.md)

核心原则：

    Project Lead
          │
          ├── People & Scheduling
          │
          └── Operations

普通问题优先由对应模块负责人处理。

跨模块或重大问题再升级至 Project Lead。

---

## 六、志愿者编号

每位正式志愿者分配唯一 Volunteer ID。

统一格式：

    V001
    V002
    V003
    ...
    V020

Volunteer ID 用于：

- 成员状态
- Availability
- 培训确认
- 正式排班
- 岗位安排
- 出勤记录
- 项目复盘

---

## 七、成员状态

成员整体准备流程：

    待邀请
       ↓
    已邀请
       ↓
    已加入
       ↓
    入组完成
       ↓
    培训完成
       ↓
    待排班
       ↓
    已排班
       ↓
    岗位确认
       ↓
    READY

成员状态表：

[`roster/volunteer-status.md`](roster/volunteer-status.md)

---

## 八、Availability

每位正式志愿者需要确认 9 月 6 日至 9 月 9 日的可参与情况。

Availability 表：

[`roster/availability.md`](roster/availability.md)

统一标记：

| 标记 | 含义 |
|---|---|
| ✅ | 可以参加 |
| ❌ | 无法参加 |
| ❓ | 尚未确认 |
| ⚠️ | 有条件参加，需要进一步协调 |

---

## 九、入组

正式确认参与后，应首先阅读：

[`docs/01-onboarding/getting-started.md`](docs/01-onboarding/getting-started.md)

入组阶段需要确认：

- GitHub 访问正常
- GitHub Username 正确
- Volunteer ID 正确
- 项目基本规则已阅读
- Availability 已提交
- 后续培训方式已知晓

---

## 十、培训

培训目录：

`docs/02-training/`

计划包含：

- 志愿者手册
- 服务规范
- 沟通礼仪
- 现场纪律
- 信息安全
- 常见问题
- 基本异常处理方式

培训资料尚在建设中。

正式成员完成规定培训后，由负责人更新培训状态。

---

## 十一、排班管理

排班总则：

[`docs/03-schedule/README.md`](docs/03-schedule/README.md)

当前已建立：

[`docs/03-schedule/2026-09-06.md`](docs/03-schedule/2026-09-06.md)

后续根据项目进度补充：

- `2026-09-07.md`
- `2026-09-08.md`
- `2026-09-09.md`

排班状态统一使用：

| 状态 | 含义 |
|---|---|
| `DRAFT` | 草案 |
| `REVIEW` | 负责人确认中 |
| `FINAL` | 正式版本 |
| `CLOSED` | 当日工作结束并归档 |

志愿者只应将 `FINAL` 状态作为正式工作安排。

---

## 十二、岗位管理

岗位目录：

`docs/04-roles/`

岗位体系将根据大会方实际现场需求建立。

在正式岗位需求未确定前，不提前虚构岗位人数。

每个正式岗位至少需要明确：

- 岗位名称
- 岗位目的
- 工作地点
- 工作时间
- 人员数量
- 主要职责
- 工作边界
- 对应负责人
- 问题升级方式
- 岗位交接要求

---

## 十三、现场运营

现场运营目录：

`docs/05-operations/`

计划包含：

- 签到 / 签退
- 迟到处理
- 请假处理
- 无法到岗处理
- 排班变更
- 临时调岗
- Incident Response
- Escalation
- 加班确认

现场工作的基本执行逻辑：

    到达集合地点
          ↓
    签到
          ↓
    找到对应负责人
          ↓
    确认岗位
          ↓
    进入工作区域
          ↓
    执行任务
          ↓
    必要时进行临时调度
          ↓
    岗位交接
          ↓
    签退
          ↓
    加班确认（如有）

---

## 十四、问题升级

正常情况下：

    志愿者
       ↓
    岗位 / 区域负责人
       ↓
    当值项目负责人
       ↓
    Project Lead
       ↓
    大会对应负责人

紧急问题优先使用即时通讯或直接联系负责人。

不要等待 GitHub Issue 回复。

问题稳定后，再根据需要补充 GitHub 正式记录。

---

## 十五、Issue 管理

后续将建立标准 Issue 模板。

计划使用：

- `[任务]`
- `[排班调整]`
- `[现场异常]`
- `[支持请求]`

示例：

    [任务] 完成志愿者培训材料

    [排班调整] V008 申请调整 9 月 7 日安排

    [现场异常] A 区临时出现人员缺口

    [支持请求] 无法访问项目仓库

Issue 用于跟踪需要负责人处理、需要留痕或者需要形成闭环的问题。

---

## 十六、信息安全

本仓库可以保存：

- Volunteer ID
- GitHub Username
- 入组状态
- 培训状态
- Availability
- 排班状态
- 岗位信息
- 出勤确认状态

本仓库不得保存：

- 身份证号码
- 身份证照片
- 银行卡信息
- 收款账户
- 家庭住址
- 账号密码
- 验证码
- 不必要的完整联系方式
- 详细医疗信息
- 候选人内部评分
- 淘汰原因
- 其他敏感个人信息

涉及身份核验、财务结算等敏感信息，应使用另外的受控渠道管理。

---

## 十七、READY 标准

一名志愿者只有在以下事项完成后，才可以进入 `READY`：

- [ ] GitHub 访问正常
- [ ] GitHub Username 已确认
- [ ] Volunteer ID 已确认
- [ ] Availability 已确认
- [ ] 入组完成
- [ ] 培训完成
- [ ] 正式排班已确认
- [ ] 岗位已确认
- [ ] 集合要求已知晓
- [ ] 现场沟通方式已知晓
- [ ] 异常升级流程已知晓

全部完成：

> **READY**

表示已经具备现场执行条件。

---

## 十八、仓库结构

当前及计划结构：

    conference-volunteer-ops-2026/
    │
    ├── README.md
    │
    ├── docs/
    │   │
    │   ├── 00-management/
    │   │   ├── responsibilities.md
    │   │   └── communication.md
    │   │
    │   ├── 01-onboarding/
    │   │   └── getting-started.md
    │   │
    │   ├── 02-training/
    │   │   ├── volunteer-handbook.md
    │   │   ├── service-standards.md
    │   │   └── faq.md
    │   │
    │   ├── 03-schedule/
    │   │   ├── README.md
    │   │   ├── 2026-09-06.md
    │   │   ├── 2026-09-07.md
    │   │   ├── 2026-09-08.md
    │   │   └── 2026-09-09.md
    │   │
    │   ├── 04-roles/
    │   │   ├── README.md
    │   │   └── role-template.md
    │   │
    │   ├── 05-operations/
    │   │   ├── check-in-check-out.md
    │   │   ├── schedule-change.md
    │   │   ├── incident-response.md
    │   │   ├── escalation.md
    │   │   └── overtime.md
    │   │
    │   └── 06-retrospective/
    │       ├── daily-review-template.md
    │       └── final-review.md
    │
    ├── roster/
    │   ├── volunteer-status.md
    │   └── availability.md
    │
    └── .github/
        └── ISSUE_TEMPLATE/
            ├── task.yml
            ├── schedule-change.yml
            ├── incident.yml
            └── support-request.yml

---

## 十九、当前建设进度

- [x] 创建项目仓库
- [x] 建立项目 README
- [x] 建立负责人职责文档
- [x] 建立入组指南
- [x] 建立成员状态表
- [x] 建立 Availability 表
- [x] 建立排班管理规则
- [x] 建立 9 月 6 日排班模板
- [ ] 建立负责人沟通规则
- [ ] 建立培训资料
- [ ] 建立岗位模板
- [ ] 建立现场运营 SOP
- [ ] 建立 Issue Templates
- [ ] 建立 GitHub Project 看板
- [ ] 三位负责人内部测试
- [ ] 正式邀请志愿者
- [ ] 完成最终 READY Review

---

## 二十、当前项目状态

**🟡 筹备中**

当前重点：

> 先完成项目管理规则、培训体系、现场 SOP 和 Issue 工作流，再补充最终每日排班。

最终目标：

> **让 3 名项目负责人能够稳定管理 20 名志愿者，并确保大会 4 天现场工作有序执行。**
