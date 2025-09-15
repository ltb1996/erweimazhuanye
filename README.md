# 专业推荐测试系统

基于Firebase的H5专业推荐问卷系统，通过QR码扫描使用。

## 快速部署

1. 安装Firebase CLI：
```bash
npm install -g firebase-tools
```

2. 登录Firebase：
```bash
firebase login
```

3. 初始化Firebase项目：
```bash
firebase init
```
选择：
- Hosting: Configure files for Firebase Hosting
- Firestore: Configure security rules and indexes

4. 部署：
```bash
firebase deploy
```

## 功能特点

- 📱 移动端优化的H5界面
- 🎯 10道精心设计的专业测试题目
- 🧠 智能分析算法，推荐最适合的专业
- 🎨 现代化UI设计，渐变色彩搭配
- ⚡ 快速部署到Firebase
- 📊 问卷结果本地分析（无需后端）

## 测试逻辑

根据用户答题选择A/B/C/D的频次，推荐对应专业类别：
- A类：理工科技类（计算机、电子、机械、数学）
- B类：人文艺术类（文学、历史、设计、传媒）
- C类：经济管理类（商管、经济、贸易、营销）
- D类：医学服务类（医学、护理、心理、社工）

## 使用方法

1. 部署后获得Firebase托管URL
2. 生成QR码指向该URL
3. 学生扫描QR码即可开始测试