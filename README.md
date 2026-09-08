# mumugaoer.github.io

个人作品集与方法论笔记站点，由 GitHub Pages 托管。

访问地址：https://mumugaoer.github.io

## 内容边界

发布前必须确认：

| 检查项 | 要求 |
|---|---|
| 企业标识 | 不得出现公司名称、Logo、内部系统名称 |
| 业务数据 | 不得出现真实金额、条款、供应商与人员姓名 |
| 原型截图 | 需去除所有标识性信息，或仅展示通用组件 |
| 方法论 | 只讲通用思路，不引用内部流程细节 |

## 目录结构

```
.
├── index.html     站点主页
├── .nojekyll      禁用 Jekyll 构建，按纯静态文件发布
└── README.md
```

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

## 更新流程

```bash
git add .
git commit -m "更新内容"
git push origin main
```

推送后 GitHub Pages 会在数十秒到数分钟内自动重新构建。

## 待办

- [ ] 替换首页作品集卡片的真实内容（脱敏后）
- [ ] 撰写三篇方法论笔记并接入链接
- [ ] 补充个人简介与联系方式
