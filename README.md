# Codex Parenting Skills

面向亲子 AI 产品、陪玩设计和内容生产工作流的可复用 Codex Skills。

## 安装

仓库加入首个稳定 Skill 后，可使用：

```bash
npx skills add gugugove05-spec/codex-parenting-skills -a codex -g -y
```

## 目录约定

```text
skills/
  skill-name/
    SKILL.md
    agents/
      openai.yaml
    scripts/
    references/
    assets/
```

每个 Skill 只包含运行所需内容。儿童照片、家庭视频、账号凭据和私有项目资料不会进入本仓库。

## 发布门槛

- `SKILL.md` 触发条件清晰、内容精简。
- 至少使用一个真实任务完成正向验证。
- 脚本能够在干净环境运行。
- 不包含绝对私人路径、密钥或儿童个人信息。
- 发布前完成静态校验和人工审阅。

## License

[MIT](LICENSE)
