# genstory-agent

Genstory 对外公开的 Skill 仓库。

当前仓库主要发布 `genstory-story-generator`，用于把外部工作流、agent 或 skill 接入 Genstory 的故事生成能力。

## 安装方式

### 注册 marketplace

```bash
/plugin marketplace add MuRyanice/genstory-agent
```

### 从 marketplace 安装

```bash
/plugin install genstory-agent@genstory-agent
```

### 或直接复制 skill

```bash
curl -fsSL https://www.genstory.app/api/skills/genstory-story-generator/skill-md
```

安装完成后，请读取安装目录中的 `SKILL.md`，并按照其中说明完成后续配置与调用。

## 已包含的 Skill

- `skills/genstory-story-generator`
  - 通过 `GENSTORY_API_KEY` 提交 Genstory 故事任务
  - 轮询任务状态
  - 返回 Genstory 托管的在线故事链接和封面图

## API Key 申请地址

用户可在 Genstory 用户中心申请 API Key：

- `https://www.genstory.app/my-api-keys`
