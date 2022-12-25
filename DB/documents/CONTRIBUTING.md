# 贡献指南

## 提交说明

- 点击右上角`fork`按钮，将项目`fork`到自己的Github账户里。
- 使用`git clone`将项目克隆到本地。

```
git clone https://github.com/forthespada/Awsome-Courses.git
```

- 用编辑器打开进行贡献，然后提交到`fork`的仓库。

```
git add .
git commit -m "What did you do?"
git push origin master
```

- 提交`Pull request`

## 完成度追踪

每添加一个页面，需在[完成度追踪表](./completeness_tracking.md)中增加相应条目。

当页面完成编辑、完成维护等状态改变时，维护者有责任在[完成度追踪表](./completeness_tracking.md)中更新对应信息。



------



## Markdown 编辑器

### Typora

为规范格式（空行、缩进等），减少多人合作编辑同一`.md`文件时的无意义的 diff 内容，推荐使用 [Typora](https://typora.io/) 编辑器。

该编辑器为类 Word 的所见即所得编辑方式，会自动按照固定格式对 Markdown 源码进行排版，从而避免手动排版与他人排版风格不匹配的问题。

------

### VSCode

若不想下载独立编辑工具，但想直观阅览 Markdown 渲染效果，则可直接使用 VSCode 编辑`.md`文件。

点击 VSCode 的`.md`文件标签页右上角的“打开侧边预览”(Ctrl+K V)，或在命令面板(F1)中搜索“Markdown”并选择打开预览(Markdown: Open Preview)即可。