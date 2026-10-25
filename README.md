# game-ui-flow

组织游戏的多页面流程、物品选择与导航状态，并验证实际操作。通用方法结合星陨弹珠的真实案例，不绑定引擎、美术风格或设备。

A portable agent skill for game interface architecture, item selection, navigation state and practical flow validation.

## 安装

将本仓库的 `game-ui-flow/` 文件夹复制到支持 Agent Skills 的工具所使用的技能目录。Codex 可安装到 `~/.codex/skills/game-ui-flow`。技能自身不要求额外运行依赖。

调用示例：`请用 $game-ui-flow 检查游戏背包与角色页的返回路径，修复已授权的问题并验证。`

## 内容

- `game-ui-flow/SKILL.md`：核心流程与调用边界。
- `game-ui-flow/references/`：导航、物品、移动布局、验证和项目案例。
- `VALIDATION.md`：实际执行的验证记录；不会将测试用例当作测试结果。

与文字、美术、实现工具协作；不自动安装其他技能，不暗含发布或改写整个游戏的权限。

## 来源与许可

本技能为项目实践整理的原创指南，MIT。方法核对参考：
- [WAI-ARIA Dialog Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/)
- [AgentSkills game-ui-design](https://github.com/jeremylongworth-source/AgentSkills/tree/main/skills/game-ui-design)（MIT；用于比较职责，没有复制其指令）
- [星陨弹珠](https://github.com/momowangOUO/arcane-pinball)（项目案例，游戏资产许可单独处理）

第三方文档与游戏原画不因本技能使用MIT而改变许可。
