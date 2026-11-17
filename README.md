# Speak through

公开练习地址：https://wa-ter-bot.github.io/speak-through/

这是「Speak through · 我的英语练习册」的公开静态构建，使用 GitHub Pages 发布。`site-v1` Release 中的 `site-public.zip` 是完整站点包；`Deploy site` workflow 会在 Release 发布或手动触发时下载、解压并部署到 Pages。

## 更新站点

1. 在本地重新构建 `out`。
2. 将 `out` 内容压缩为 `site-public.zip`，保持 `index.html` 位于压缩包根目录。
3. 覆盖上传到 `site-v1` Release 的 `site-public.zip`。
4. 手动运行 `Deploy site` workflow。

## 账号同步

公开站点的 Appwrite Web 平台需要包含 `wa-ter-bot.github.io`。未登记时仍可本机练习，登录/云同步会提示网络不可用；原站不受影响。