# Discord Youtube音樂機器人

此 Discord 機器人旨在提供音樂播放和基礎管理功能。以下是可用的指令和功能。
Discord.js v14

邀請連結在下方！

此機器人為 https://github.com/rickwengdev/Discord-bot 的音樂輕量版，只有音樂功能並且可以直接邀請進伺服器使用，無需部署！！

## 音樂指令(目前僅支援Youtube)

- `/music_play`
  - **描述**：播放播放列表中的歌曲。

- `/music_add`
  - **描述**：將歌曲添加到播放列表。
  - **參數**：
    - `url`（必填）：要添加的歌曲的 URL。

- `/music_remove`
  - **描述**：從播放列表中刪除指定的歌曲。
  - **參數**：
    - `url`（必填）：要刪除的歌曲的 URL。

- `/music_showplaylist`
  - **描述**：顯示當前播放列表。

- `/music_skip`
  - **描述**：跳轉到播放列表中的下一首歌曲。

- `/music_stop`
  - **描述**：停止播放當前歌曲。

## 邀請連結

https://discord.com/oauth2/authorize?client_id=1270576259231121499&permissions=274881060352&integration_type=0&scope=bot

## 本地部署

1. 克隆存儲庫。

  ```bash
  git clone https://github.com/rickcompanydev/Music_bot_global.git
  ```
2. 新增 .env 文件

  ```.env
  token=your bot token
  clientId=your bot APPLICATION ID
  ```
3. 建立 Docker。

  ```bash
  docker build -t discord_music_bot .
  ```
4. 運行 Docker
  
  ```bash
  docker run --rm -it  discord-bot:latest
  ```


### 貢獻

如果您有興趣為此機器人做出貢獻，請參閱我們的 [貢獻準則](https://github.com/rickcompanydev/Music_bot_global/blob/master/CONTRIBUTING.md)。

### 問題和反饋

如果您遇到任何問題或有建議，請在 [GitHub 存儲庫](https://github.com/rickcompanydev/Music_bot_global) 中提交問題。

感謝您使用我們的 Discord 機器人！