![FreeCodeCamp logo](/images/FCC-China.jpg)

## Agenda for the February 2th video call of FFC China core technical team

- **Host**: Google Hangouts
- **Dates**: Saturday February 5th, 2018
- **Times**: 22:00 Beijing Time
- **Location**: *same Google Hangouts link as before*
- **Contact**:
    - Name: Jason Yu
    - Email: yhorg@hotmail.com

### Registration

None required if you've attended before. 

## Logistics

The meeting will be a Google Hangouts call.

## Agenda items

1. Opening, welcome and roll call
    1. Opening of the meeting
    1. Introduction of attendees
1. Find volunteers for note taking
1. Adoption of the agenda
1. Proposals and discussions
    1. Review of action items from prior meeting.
    1. 技术组协作方式，是否需要拆分成各个行动小组？还是按照个人意愿进行参与？
    1. 技术组代码库的维护方式，按照部分一致原则来进行代码审阅，参见[PMCR-1]，代码发布固定时间和操作人[PMCR-2]。
    1. 技术组公共资源的搭建与整合，现阶段是否需要维护技术博客？是否有时间得到内容更新？
    1. Discuss upcoming in-person meetings.
1. Closure

## Pre-meeting content review [PMCR]

**PMCR-1**. 针对代码库的代码审阅和上线发布流程，我们可以采用部分一致的方式来进行。代码发布流程采用 Forking 工作流的方式进行，代码在被合并到主分支前，代码提交人需要确保该次 PR 至少得到三位团队核心成员的 Approval 确认。代码被合并到主分支后需要在测试环境进行测试后才可以被发布到线上环境。

**PMCR-2**. 可以采取成立"代码发布及审核小组"的方式来进行代码的审阅及发布。生产环境的代码发布需要确保在"北京时间11时"后进行。
## Agenda items for future meetings

*None*

### Schedule constraints

*None*

## Meeting notes


1. 需要一个标准的代码发布流程 SOP 文档（从代码提交到发布上线）。**飞雪和星星负责整理初版**

2. 与核心团队沟通 FCC BETA 版本的版权问题、开发进度以及稳定性等，确认是否可以开始进行翻译。**Miya 负责沟通**

3. 团队分成两个小组：**开发小组**和**翻译小组**。小组成员可重复，保持机动性。

4. 编写用于测试服务器环境的 Dockerfile，用于搭建本地测试环境。**于航和水歌负责**

5. 代码发布采用定期迭代方式，暂定**每周日 23:00 时**。

6. 简书、掘金和知乎专栏，暂定待主要业务（代码、翻译以及主页等）稳定后再开始进行。**所有人**

7. 代码测试流程：本地 Doker 环境下测试 -> 从 Forking 仓库提交 PR 到开发分支 -> 开发分支在线上测试服务测试 -> 合并主要分支 -> 发布代码。 **所有人**

8. 代码审核环节采用 Peer Review 方式，至少团队内部三人以上审核通过后才可进行合并。 **所有人**

