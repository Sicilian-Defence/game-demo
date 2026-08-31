这个Content文件夹转存在UE5的项目文件夹里面了，不在game-demo根目录下了


Content/
│
├── Art/                          ← 所有美术资源(美术与UI负责管理)
│   ├── Characters/               ← 角色
│   │   ├── Player/               ← 玩家角色
│   │   │   ├── Meshes/           ← 模型
│   │   │   ├── Textures/         ← 贴图
│   │   │   ├── Materials/        ← 材质
│   │   │   └── Animations/       ← 动画
│   │   └── NPC/                  ← NPC/敌人
│   │       ├── Meshes/
│   │       ├── Textures/
│   │       ├── Materials/
│   │       └── Animations/
│   │
│   ├── Environment/              ← 环境场景
│   │   ├── Terrain/              ← 地形（地形材质、高度图）
│   │   ├── Vegetation/           ← 植被（树、草、岩石）
│   │   ├── Buildings/            ← 建筑
│   │   └── Props/                ← 场景道具（箱子、路障、车辆）
│   │
│   ├── Weapons/                  ← 武器系统
│   │   ├── Rifles/               ← 步枪
│   │   │   ├── Meshes/
│   │   │   ├── Textures/
│   │   │   └── Materials/
│   │   ├── Pistols/              ← 手枪
│   │   └── Attachments/          ← 配件（瞄准镜、消音器）
│   │
│   ├── FX/                       ← 特效
│   │   ├── Particles/            ← 粒子系统（枪口火焰、爆炸）
│   │   ├── Decals/               ← 贴花（弹孔、血迹）
│   │   └── Niagara/              ← Niagara特效系统
│   │
│   └── UI/                       ← UI美术资源（图标、图片、字体）
│       ├── Icons/                ← 武器图标、技能图标
│       ├── HUD/                  ← HUD背景、边框
│       └── Fonts/                ← 字体文件
│
├── Blueprints/                   ← 所有蓝图（程序主管区域）
│   ├── Characters/               ← 角色蓝图
│   ├── Weapons/                  ← 武器蓝图
│   ├── Gameplay/                 ← 游戏逻辑
│   ├── UI/                       ← UI蓝图
│   └── Props/                    ← 交互道具蓝图
│
├── Core/                         ← 核心系统（程序主管区域）
│   ├── GameModes/                ← 游戏模式（不同模式的配置）
│   ├── PlayerControllers/        ← 玩家控制器
│   ├── GameInstances/            ← 游戏实例（跨关卡数据）
│   └── SaveGames/                ← 存档系统
│
├── Audio/                        ← 音频资源
│   ├── SFX/                      ← 音效（枪声、脚步声、环境声）
│   ├── Music/                    ← 背景音乐
│   └── Dialogues/                ← 对话语音
│
├── Maps/                         ← 关卡地图
│   ├── Levels/                   ← 游戏关卡
│   └── SubLevels/                ← 子关卡（用于流式加载）
│
├── Data/                         ← 数据表
│   ├── DataTables/               ← 数据表（武器属性、物品掉落）
│   └── Curves/                   ← 曲线资产（后坐力曲线、成长曲线）
│
└── Docs/                         ← 文档
    ├── AssetReference.xlsx       ← 资源引用清单
    └── NamingConvention.md       ← 命名规范
