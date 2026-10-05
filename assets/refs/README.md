# 参考图说明

把角色参考图放到本目录，命名如下：

| 文件名 | 用途 | 建议 |
|---|---|---|
| `face.png` | 脸部参考：锁死脸型、眼睛、鼻、嘴、刘海 | 正面特写，白底或干净背景最佳 |
| `body.png` | 全身参考：锁死全身比例、头发、服装 | 站立全身像 |

- 格式：PNG / JPEG / WebP
- 生图时在 `media.generate_image` 的 prompt 数组里用 `{"kind": "image", "value": "<skill-dir>/assets/refs/face.png"}` 传入
- 没有参考图也能跑：只用文字 prompt 里的角色锁定词（见 `SKILL.md` §0.3）
- **不要把真人照片放这里**（安全边界要求）
