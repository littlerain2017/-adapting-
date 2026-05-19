# -adapting-

短剧与电影剧本创作 Claude Code Skills 仓库。

## Skills

| Skill | 用途 |
|-------|------|
| [drama-creator](skills/drama-creator/) | 从零创作竖屏短剧剧本（宏观建构、悬念设计、逐集输出） |
| [drama-analyzer](skills/drama-analyzer/) | 分析小说/剧本，提炼情节点与戏剧功能 |
| [drama-evaluator](skills/drama-evaluator/) | 评估故事改编为短剧的潜力与市场竞争力 |
| [drama-workflow](skills/drama-workflow/) | 协调长文本的改编分析流程（并行分析 + 结果整合） |
| [drama-adaptation](skills/drama-adaptation/) | 将短剧改编为院线电影或20分钟剧集 |
| [screenplay-evaluator](skills/screenplay-evaluator/) | 依据好莱坞 Script Coverage 标准评估院线电影剧本，输出 Pass/Consider/Recommend 评级 |

## 安装

```bash
# 克隆仓库
git clone https://github.com/littlerain2017/-adapting-.git

# 安装所有 skills
cp -r -adapting-/skills/* ~/.claude/skills/

# 或单独安装某个
cp -r -adapting-/skills/screenplay-evaluator ~/.claude/skills/screenplay-evaluator
```
