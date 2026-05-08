# WiseMindAI Desktop Pet

这是一个为 Codex 制作的 WiseMindAI 桌面宠物。

它是一只绿色学习陪伴小宠物，带有圆润的方块身体、黑色亮眼睛、粉色脸颊、白色小翅膀和头顶小芽。它的定位不是单纯装饰，而是作为 WiseMindAI 的学习陪伴形象，适合在阅读、记笔记、复习和专注工作时使用。

## 预览

你可以在 Codex 的宠物设置中启用它。宠物包含待机、移动、挥手、跳跃、等待、失败、忙碌中、审阅等动作状态。

<img src="./demo.gif" />

## 文件说明

项目中主要包含两个文件：

```text
pet.json
spritesheet.webp
```

`pet.json` 是宠物配置文件，里面包含宠物名称、介绍和精灵图路径。

`spritesheet.webp` 是宠物动作图，里面包含所有动画帧。

## 安装方法

把整个 `wisemindai` 文件夹复制到 Codex 的宠物目录：

```text
~/.codex/pets/
```

复制后目录结构应该类似这样：

```text
~/.codex/pets/wisemindai/
├── pet.json
├── spritesheet.webp
├── demo.gif
└── README.md
```

然后重启 Codex。

## 使用方法

1. 打开 Codex。
2. 进入宠物或外观相关设置。
3. 在宠物列表中找到 `WiseMindAI`。
4. 选择并启用它。

如果没有马上看到这个宠物，可以先确认文件夹路径是否正确，然后重启 Codex 再试一次。

## 宠物信息

名称：WiseMindAI

介绍：WiseMindAI learning companion pet: a cheerful green desktop buddy that keeps you company while reading, taking notes, reviewing, and staying focused.

## 自定义说明

如果你想基于这个宠物继续修改，可以替换 `spritesheet.webp`，但需要保持 Codex 宠物要求的精灵图格式。

如果只是想改显示名称或介绍，可以直接编辑 `pet.json`：

```json
{
  "id": "wisemindai",
  "displayName": "WiseMindAI",
  "description": "WiseMindAI learning companion pet: a cheerful green desktop buddy that keeps you company while reading, taking notes, reviewing, and staying focused.",
  "spritesheetPath": "spritesheet.webp"
}
```

## 适合谁使用

这个宠物适合 WiseMindAI 用户、Codex 用户，以及想让桌面工作环境更有陪伴感的人。

它不会改变 Codex 的核心功能，只是让日常使用多一个轻量、可爱的学习陪伴入口。
