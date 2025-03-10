# 功能升级日志
# 2.14.5
- 😄 新增： midjourney wsrv访问图片
# 2.14.4
- 🐞 修复：手机端的页面绘画不出图 #59
- 🐞 修复：midjourney 强制刷新不起作用
# 2.14.3
- 😄 新增： 角色自定到会话 #75 #40
- 😄 新增： 支持one-api部署聊天 https://vercel.ddaiai.com/#/?settings={%22key%22:%22sk-abc%22,%22url%22:%22https://api.openai.com%22}

# 2.14.2
- 🐞 修复： gpt-4-1106-preview 模型 128000 #66
- 😄 新增： 录音whisper转文本对话ChatGPT
- 😄 新增： 对话内容tts转语音
- 😄 新增： 文件上传支持 `cloudflare r2 存储` 感谢 @xuzhenjun130 PR

# 2.14.1
- 🐞 修复： gpt-4-1106-preview 模型 128k #66
- 🐞 修复： 余额显示方式 #61
- 😄 新增： `DISABLE_GPT4=1` 控制不让用 GPT-4 #65
- 😄 新增： `OpenAi Api Key 错误` 对话框中出现引导设置

# 2.13.10
- 🔨 优化： 输入实时计算剩余tokens #63
- 🐞 修复： 重新获取bug

# 2.13.9
- 😄 新增： 超链设置

# 2.13.8
- 🐞 修复： #55 将画图提示词加到2000字
- 🔨 优化： 上传.加入进度条
- 😄 新增： midjourney `清设置`按钮
- 😄 新增： midjourney `自定义变焦`功能


# 2.13.7
- 🐞 修复： #55 名称错误
- 😄 新增： midjourney shorten 操作
- 🐞 修复： 手机端无GPTs入口

# 2.13.6
- 🔨 优化： UI服务端保存
- 😄 新增： 国际化语言包

## 2.13.5
- 🐞 修复： 历史记录未带附件链接
- 😄 新增： 系统通知 #47

## 2.13.4
- 🐞 修复： midjourney 参数不起作用

## 2.13.3
- 😄 更新： 更新本月使用量、余额的请求方式

## 2.13.2 
- 🐞 修复： midjourney 刷新错误
- ✅ 新增： tts whisper 界面支持
- 😄 新增： midjourney 新增 V6


## 2.13.1 
- 🐞 修复： gpts 加载排序
- 😄 新增： google、百度统计
- 😄 新增： 文件支持拖拽上传、粘贴截图上传 #39


## 2.12.11 
- 🐞 紧急修复： gpt-4-vision-preview 格式错误

## 2.12.10 
- 🐞 修复：希望实现左侧绘画功能区固定，不随对话界面上下滚动 #29
- 🐞 修复：当服务端有错误，ui错误显示为空bug 
- 🔨 优化：新增 `CUSTOM_MODELS` 环境变量 可自定义可选模型 #32
 


## 2.12.9 
- 🐞 修复：按住回车不放，会一直触发提交刷新页面 #24
- 🔨 优化：我的画廊 支持来之服务端的数据（适合自建服务器）
- 🔨 优化：midjourney 新增 `原始链接` 按钮

## 2.12.8
- 😄 新增：我的画廊
- 🐞 修复：重试按钮、停止按钮功能 #15


## 2.12.7
- 😄 新增：vercel 增加 AUTH_SECRET_KEY 可以访问输入验证 #15
- 🐞 修复：OPENAI_API_MODEL 默认模型 同时支持 vercel #16
- 🐞 修复：在手机端左侧没法下滑 #18


## 2.12.6
- 🐞 修复：`经常出现“新建聊天框”遮挡对话框的情况 ` #13
- 🐞 修复：当GPTS在绘画窗口，切换不起效果
- 🐞 修复：分页载入GPTs计数出现的问题

## 2.12.5
- 🔨 优化：丰富 GPTS 内容，可以搜索
- 😄 新增：前端UI 设置 上传文件入口 #11
- 🐞 修复：`经常出现“新建聊天框”遮挡对话框的情况 ` #13


## 2.12.4
- 😄 新增 dall-e-2模型
- 🐞 修复：上传错误提示为空
- 🐞 修复：`环境变量中配置的OPENAI_API_BASE_URL和OPENAI_API_KEY依旧没有效果，前端对话一直处于“思考中...”` #4

## 2.12.3
- 😄 新增 支持超链模型切换 http://ip:6013/#/m/gpt-4-all http://ip:6013/#/m/gpt-4-gizmo-1234
- 😄 新增 支持 GPTs 多模态

## 2.12.2
- 😄 新增：支持文件后端上传（供给gpt-4-all gpt-4-gizmo-xxx 模型）！ 默认是关闭的 打开需要环境变量 API_UPLOADER=1
- 😄 新增：支持逆向模型 gpt-4-all gpt-4-v gpt-4-gizmo-(gizmo_id)

## 2.12.1
- 😄 新增：图片上传图片 供gpt-4-vision-preview使用
- 🐞 修复:：midjourney 辅助提示“模型版本” 去掉早期过时版本

## 2.11.10
- 🐞 修复：dall-e-3的大小规格
- 😄 新增：gpt模型选择
- 😄 新增：gpt自定义模型、上下文数、回复数
- 🔩 更改：流请求方式由原来的axios改为fetch 打字效果更加顺滑

## 2.11.9 
- 😄 新增：dall-e-3 画图 
## 2.11.8
- 🐞 修复：midjourney 辅助提示“性格” 出现的bug
- 😄 新增：最新版本检查
- 😄 新增：midjourney 获取seed

## 2.11.7
- 😀 新增：midjourney 换脸
- 😀 新增：midjourney 混图