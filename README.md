# StarX

学习通 LSPosed 模块。

主要功能：

- 跳过启动广告（免激活即可使用）
- 签到、题库、考试搜题与自动答题（需激活）
- 章节测验 iframe 搜题与自动答题（需激活）
- 视频任务辅助（需激活）
- 多题库协议：LemTk / tikuAdapter / ZXSeek / Wkexam
- AI 搜题（OpenAI / Gemini，BYOK）

## 下载与反馈

- 版本发布：<https://github.com/Xposed-Modules-Repo/org.xiyu.starx/releases>
- 源码与公测反馈（提 issue 到这里）：<https://github.com/Mai-xiyu/StarX>
- 公测清单：<https://github.com/Mai-xiyu/StarX/blob/main/PUBLIC_TEST_CHECKLIST.md>

## 使用前置

1. LSPosed（ZygiskOnKernelSU / Xposed API 100+）
2. 学习通 6.7.x（当前构建针对 6.7.4 校验）
3. 在 LSPosed 中启用本模块，作用域勾选 `com.chaoxing.mobile`
4. 打开 StarX 应用进入设置（激活、题库、AI Key 等）

## 提 issue 前建议准备

- StarX 版本
- 学习通版本
- Android 版本、机型、LSPosed 版本
- 具体页面入口和复现步骤
- 复现后的日志、截图或录屏

导出日志：

```powershell
adb logcat -d -s StarX:D *:S
```

## 免责声明

本模块仅用于学习研究与个人辅助使用，严禁用于任何违反法律法规或学校规定的场景。
使用本模块造成的任何后果由使用者自行承担。
