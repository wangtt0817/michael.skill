# Michael_Liu93 Skill

`Michael_Liu93` 主导、`gas1618` 风险滤镜增强的加密市场交易决策与市场分析 Skill。

## 目录说明

- `SKILL.md`
  - 初版主 Skill

- `merge-rules.md`
  - 合并规则与冲突处理

- `sources.md`
  - 来源清单

- `docs/research-log.md`
  - 试跑与验证记录

- `deliverables/standard-skill/michael-liu93-gas1618/`
  - 标准可安装 Skill 目录

- `deliverables/standard-skill/michael-liu93-gas1618-standard-skill.zip`
  - 标准 Skill 压缩包

## 推荐发布内容

最推荐发布的是这个标准目录：

- `deliverables/standard-skill/michael-liu93-gas1618/`

以及这个压缩包：

- `deliverables/standard-skill/michael-liu93-gas1618-standard-skill.zip`

## GitHub 下载渠道

假设你的仓库地址是：

```text
https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME
```

那么可提供这些下载方式。

### 1. 仓库主页浏览

```text
https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME
```

### 2. 直接下载主分支 ZIP

```text
https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/archive/refs/heads/main.zip
```

### 3. Releases 下载标准 Skill ZIP

把下面这个文件上传到 GitHub Release：

- `deliverables/standard-skill/michael-liu93-gas1618-standard-skill.zip`

对应下载链接模板：

```text
https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/releases/download/v1.0.0/michael-liu93-gas1618-standard-skill.zip
```

### 4. 单文件 Raw 下载 `SKILL.md`

```text
https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/SKILL.md
```

### 5. 单文件 Raw 下载 `merge-rules.md`

```text
https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/references/merge-rules.md
```

### 6. 单文件 Raw 下载 `sources.md`

```text
https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/references/sources.md
```

### 7. `git clone`

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
```

## 一条命令安装

发布到 GitHub 后，如果用户想直接安装到本地 Codex skills 目录，可以用这条 PowerShell：

```powershell
$root="$env:USERPROFILE\.codex\skills\michael-liu93-gas1618"; New-Item -ItemType Directory -Force -Path $root | Out-Null; Invoke-WebRequest "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/SKILL.md" -OutFile "$root\SKILL.md"; New-Item -ItemType Directory -Force -Path "$root\agents","$root\references" | Out-Null; Invoke-WebRequest "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/agents/openai.yaml" -OutFile "$root\agents\openai.yaml"; Invoke-WebRequest "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/references/merge-rules.md" -OutFile "$root\references\merge-rules.md"; Invoke-WebRequest "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/references/sources.md" -OutFile "$root\references\sources.md"; Invoke-WebRequest "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/deliverables/standard-skill/michael-liu93-gas1618/references/research-log.md" -OutFile "$root\references\research-log.md"
```

