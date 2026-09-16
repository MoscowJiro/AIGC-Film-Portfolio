# THE HUNT｜猎

> 一部结合 3D Previsualization、Virtual Cinematography  
> 与 Generative Filmmaking 完成的电影短片。

![THE HUNT](THE%20HUNT/01_FINAL/Cover.png)

**编剧 / 导演：Jiahui Hong**

2026 · 约 1 分钟 · Psychological Horror / Medieval Realism

[观看或下载完整影片 →](THE%20HUNT/01_FINAL/THE%20HUNT.mp4)

---

## 项目简介｜Overview

三名败逃的士兵穿过一片寒冷、潮湿的森林。

浓雾之中，一个身份不明的披甲身影正无声逼近。

**THE HUNT** 没有将每个镜头作为独立画面生成。正式制作前，影片先后完成了剧本、Master Shot List、Visual Bible、World Blocking、Camera Blocking，以及完整的 Blender Previs。

这些前期工作为后续生成建立了统一的空间、角色和镜头逻辑。

| 片长 | 镜头数 | 场景范围 | Previs 时长 |
|:---:|:---:|:---:|:---:|
| 约 1 分钟 | 24 Shots | 90 × 110 m | 约 66 秒 |

本项目尝试回答一个问题：

**3D Previsualization 能否为 Generative Filmmaking 提供更可靠的空间连续性、角色一致性与导演控制？**

---

## 成片｜Final Film

[▶ 观看或下载 THE HUNT](THE%20HUNT/01_FINAL/THE%20HUNT.mp4)

### Final Stills

![THE HUNT — Final Stills](THE%20HUNT/01_FINAL/Final%20Stills.jpg)

---

## 前期开发｜Pre-Production

### 剧本｜Script

影片采用四幕追逐结构：

**ESCAPE → THE KNIGHT → THE FIGHT → THE HUNT**

故事从逃亡进入对峙，最终转变为一场无法摆脱的追猎。

[阅读完整剧本 →](THE%20HUNT/02_PREPRODUCTION/script.md)

### 镜头表｜Master Shot List

剧本被拆解为一份完整的 **24-shot Master Shot List**。

每个镜头分别定义了构图、Camera Behavior、角色动作、时间长度和叙事功能。

[查看 Master Shot List →](THE%20HUNT/02_PREPRODUCTION/Master_Shot_List.md)

---

## 视觉设定｜Visual Bible

正式制作前，项目先建立了一套 Visual Bible，用于统一角色、环境、武器装备和整体视觉语言。

目标不是制造奇幻感，而是在不同镜头之间维持同一个可信的中世纪世界。

### 角色设计｜Character Design

| Character A | Character B |
|:---:|:---:|
| ![Character A](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_A_Design.png) | ![Character B](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_B_Design.png) |

| Character C | The Knight |
|:---:|:---:|
| ![Character C](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_C_Design.png) | ![The Knight](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/The_Knight_Design.png) |

### 角色转面｜Character Turnarounds

每个角色均制作了 Multi-view Turnaround，用于固定面部、服装、盔甲、装备和人物轮廓。

[Character A →](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_A_Turnaround.png) ·
[Character B →](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_B_Turnaround.png) ·
[Character C →](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/Character_C_Turnaround.png) ·
[The Knight →](THE%20HUNT/03_VISUAL_BIBLE/CHARACTERS/The_Knight_Turnaround.png)

### 环境设计｜Environment Design

故事发生在日出后的第一个小时。

冷色天光、潮湿黑泥、浅水、浓雾和欧洲原始森林共同构成影片的环境基调。

| Environment 01 | Environment 02 | Environment 03 |
|:---:|:---:|:---:|
| ![Environment 01](THE%20HUNT/03_VISUAL_BIBLE/ENVIRONMENT/Environment_01.png) | ![Environment 02](THE%20HUNT/03_VISUAL_BIBLE/ENVIRONMENT/Environment_02.png) | ![Environment 03](THE%20HUNT/03_VISUAL_BIBLE/ENVIRONMENT/Environment_03.png) |

### 视觉基准｜Visual Benchmark

在进入镜头制作前，项目锁定了一张 Visual Benchmark，用于统一光线、色彩、雾气密度和材质表现。

![THE HUNT Visual Benchmark](THE%20HUNT/03_VISUAL_BIBLE/ENVIRONMENT/Visual_Benchmark.png)

### 武器与装备｜Equipment Design

武器和装备与角色同步设计，作为后续镜头中的 Prop Continuity 参考。

![Weapon Sheet](THE%20HUNT/03_VISUAL_BIBLE/EQUIPMENT/Weapon_Sheet.png)

---

## 三维场景规划｜3D World Blocking

影片的全部镜头发生在同一个连续空间中。

一个 **90 × 110 m 的 World Master Scene** 定义了森林地形、人物位置、移动路线、战斗区域和遭遇距离。

### Spatial System

- **90 × 110 m** 森林场景
- **313** 个 Tree Proxies
- **20 × 28 m** 中央遭遇区域
- 四名角色的连续 Movement Paths
- **15 m** 最终对峙距离
- **41.36 m** 最终逃亡路线

### World Overview

![3D World Overview](THE%20HUNT/04_PREVIS/01_WORLD_BLOCKING/WORLD_3D_OVERVIEW.png)

### Top-Down Layout

| Master Layout | Detailed Layout |
|:---:|:---:|
| ![World Top View](THE%20HUNT/04_PREVIS/01_WORLD_BLOCKING/WORLD_TOP_VIEW.png) | ![World Top View Detail](THE%20HUNT/04_PREVIS/01_WORLD_BLOCKING/WORLD_TOP_VIEW_DETAIL.png) |

World Master Scene 为角色调度、机位设计和 Blender Previs 提供了统一的空间基础。

[查看 World Master Scene 文档 →](THE%20HUNT/04_PREVIS/01_WORLD_BLOCKING/README.md)

---

## 机位设计｜Camera Blocking

空间关系确定后，影片的 24 个镜头被放入同一个 Master Scene 中完成 Camera Blocking。

机位、构图、Screen Direction 和角色位置均在最终生成前确定，以维持三名士兵与 The Knight 之间连续、可判断的空间关系。

### 24-Shot Camera Plan

![Camera Blocking Contact Sheet](THE%20HUNT/04_PREVIS/02_CAMERA_BLOCKING/Camera_Blocking_Contact_Sheet.png)

### Camera Design

| Camera View | Camera Layout |
|:---:|:---:|
| ![Camera Blocking View](THE%20HUNT/04_PREVIS/02_CAMERA_BLOCKING/Camera_Blocking_View.png) | ![Camera Layout](THE%20HUNT/04_PREVIS/02_CAMERA_BLOCKING/Camera_Layout.png) |

### Storyboard

![Storyboard Contact Sheet](THE%20HUNT/04_PREVIS/02_CAMERA_BLOCKING/Storyboard_Contact_Sheet.png)

---

## Blender 预演｜Blender Previs

World Master Scene 和 24-shot Camera Plan 随后被整合进 Blender，形成覆盖全片的 Previsualization。

这些画面并不是最终成片，而是用于验证：

- Composition
- Camera Movement
- Character Blocking
- Screen Direction
- Timing
- Spatial Continuity

### Blender Scene

| Perspective View | Top View |
|:---:|:---:|
| ![Blender Perspective View](THE%20HUNT/04_PREVIS/03_BLENDER/BLENDER_PERSPECTIVE_VIEW.png) | ![Blender Top View](THE%20HUNT/04_PREVIS/03_BLENDER/BLENDER_TOP_VIEW.png) |

### Scene Structure

![Blender Hierarchy](THE%20HUNT/04_PREVIS/03_BLENDER/BLENDER_HIERARCHY.png)

最终 Previs 建立了约 **66 秒**的连续影像结构。影片的节奏、动作和空间逻辑因此能够在进入生成阶段前被完整检查。

> **Previs 是导演工具，不是最终画面。**

---

## 生成制作｜Generative Production

完成 Visual Bible、World Blocking 和 Blender Previs 后，项目才进入 Generative Production。

每个镜头都同时使用：

- Character References
- Environment References
- Previs Composition
- Camera Direction
- Iterative Generation

生成工具负责画面实现，但不负责决定影片的空间和镜头结构。

### Production Board

![Generative Production Board](THE%20HUNT/04_PREVIS/04_GENERATIVE_WORKFLOW/Generative_Production_Board.png)

Production Board 将角色、环境、构图和镜头生成参考集中在同一个视觉系统中。

---

## 制作流程｜Production Pipeline

```text
SCRIPT
  ↓
MASTER SHOT LIST
  ↓
VISUAL BIBLE
  ↓
3D WORLD BLOCKING
  ↓
CAMERA BLOCKING
  ↓
BLENDER PREVIS
  ↓
GENERATIVE PRODUCTION
  ↓
EDITING & SOUND DESIGN
  ↓
FINAL FILM

---

使用工具｜Tools
Tool	用途
GPT-6 Astra	项目规划、Workflow Assistance、Production Development
Blender	World Blocking、Camera Blocking、Previsualization
Midjourney	Visual Development、Reference Generation
LibTV	Generative Production Workflow
Seedance 2.5	Video Generation
CapCut	Editing、Sound Design、Final Assembly

---

项目文件｜Project Files
仓库中包含部分制作文件，用于展示影片背后的技术结构。
- [Blender World Master](THE HUNT/05_PROJECT_FILES/THE_HUNT_WORLD_MASTER.blend)
- [World Master Scene — GLB](THE HUNT/05_PROJECT_FILES/WORLD_MASTER_SCENE.glb)
- [World Layout Data](THE HUNT/05_PROJECT_FILES/world_layout.json)
- [Interactive World Master Viewer](THE HUNT/04_PREVIS/01_WORLD_BLOCKING/WORLD_MASTER_VIEWER.html)
这些文件属于制作过程记录，不影响成片观看。

---

主创｜Credits
THE HUNT｜猎
编剧 / 导演
Jiahui Hong
视觉开发｜Visual Development
Jiahui Hong
预演与虚拟摄影｜Previsualization & Virtual Cinematography
Jiahui Hong
AI-Assisted Production
LibTV · Seedance 2.5 · GPT-6 Astra · Blender · Midjourney
剪辑与声音设计｜Editing & Sound Design
Jiahui Hong
2026
