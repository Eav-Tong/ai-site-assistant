# 个人管理系统

一个功能完善的个人管理系统，帮助你高效管理任务、日程、笔记和目标。

## 功能特性

- **任务管理** - 创建、编辑、完成任务，支持优先级和截止日期
- **日程管理** - 日历视图，安排每日活动
- **笔记管理** - 快速记录想法，支持分类和搜索
- **目标追踪** - 设定长期目标，追踪进度
- **数据统计** - 可视化展示完成情况和使用建议

## 技术栈

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (图标库)
- LocalStorage (数据持久化)

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产构建

```bash
npm run preview
```

## 项目结构

```
src/
├── components/          # 组件目录
│   ├── Dashboard.tsx   # 数据统计面板
│   ├── TaskManager.tsx # 任务管理
│   ├── ScheduleManager.tsx # 日程管理
│   ├── NoteManager.tsx # 笔记管理
│   └── GoalManager.tsx # 目标追踪
├── types.ts            # TypeScript 类型定义
├── storage.ts          # LocalStorage 数据持久化
├── App.tsx             # 主应用组件
├── main.tsx            # 应用入口
└── index.css           # 全局样式
```

## 使用说明

1. **数据统计** - 查看任务、日程、笔记和目标的完成情况
2. **任务管理** - 添加新任务，设置优先级和截止日期，标记完成
3. **日程管理** - 在日历上查看和添加日程安排
4. **笔记管理** - 创建笔记，支持分类和搜索功能
5. **目标追踪** - 设定目标，通过滑块更新进度

## 数据存储

所有数据都存储在浏览器的 LocalStorage 中，数据会自动保存，刷新页面不会丢失。

## 响应式设计

系统支持桌面和移动设备，在移动端会自动适配布局。

## 许可证

MIT
