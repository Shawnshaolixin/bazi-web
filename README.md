# 八字排盘网页工具

基于 Next.js + Tailwind CSS 的八字排盘网页工具 MVP。

## 功能

- 出生信息输入
- 公历 / 农历切换
- 性别选择
- 高级设置（出生地、时区、真太阳时、闰月）
- 八字结果页
- 四柱排盘展示
- 五行统计展示
- 基础术语说明
- 分享与复制结果链接

## 技术栈

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS 4

## 本地开发

```bash
npm install
npm run dev
```

打开 `http://localhost:3000`。

## 项目结构

```text
app/
  page.tsx              首页
  result/page.tsx       结果页
components/
  bazi/                 业务组件
lib/bazi/               排盘数据与类型
```

## 说明

当前为 MVP 版本：
- 已完成页面结构与交互流程
- 当前使用演示数据生成结果页
- 后续可接入真实历法与八字计算算法

## 合规提示

本工具基于传统文化内容整理，仅供娱乐与参考，不构成任何专业建议。
