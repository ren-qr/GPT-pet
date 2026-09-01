# GPT-chan Codex 桌宠

![GPT-chan promotional banner](assets/gpt-chan-promo.png)

GPT-chan 是一款适用于 Codex 桌面版的自定义动态桌宠。

## 动作预览

| Idle | Waving |
| --- | --- |
| ![Idle animation](assets/previews/idle.gif) | ![Waving animation](assets/previews/waving.gif) |
| Running | Waiting |
| ![Running animation](assets/previews/running.gif) | ![Waiting animation](assets/previews/waiting.gif) |

<details>
<summary>查看完整动作图和 16 向视线预览</summary>

![All animation frames](assets/previews/actions-contact-sheet.png)

![16 look directions](assets/previews/look-directions.png)

</details>

## 安装

### 使用终端

在 macOS 终端中运行：

```bash
git clone https://github.com/ren-qr/GPT-pet.git
mkdir -p ~/.codex/pets
cp -R GPT-pet/gpt-chan ~/.codex/pets/gpt-chan
```

完成后重启 Codex，在桌宠设置中选择 **GPT-chan**。

### 手动安装

1. 下载本仓库的 ZIP 文件并解压。
2. 在 Finder 中打开 `~/.codex/pets/`；目录不存在时请先创建。
3. 将完整的 `gpt-chan` 文件夹复制到 `~/.codex/pets/`。
4. 重启 Codex，在桌宠设置中选择 **GPT-chan**。

安装后的目录结构：

```text
~/.codex/pets/gpt-chan/
├── pet.json
└── spritesheet.webp
```

## 要求

- 支持自定义桌宠的 Codex 桌面版
- Sprite format version 2
