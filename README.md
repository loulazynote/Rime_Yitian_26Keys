# RIME 倚天26鍵輸入方案（Windows）

## 安裝方式
- 將下列檔案複製進用戶資料夾:
	- Windows: `%APPDATA%\Rime`
	- Linux (fcitx5): `~/.local/share/fcitx5/rime/`
	- Linux (IBus): `~/.config/ibus/rime/`
	- MacOS: `~/Library/Rime/`

  > 倚天26鍵 RIME輸入方案 : 
  >    - yitian_26Keys.dict.yaml
  >    - yitian_26Keys.extended.dict.yaml
  >    - yitian_26Keys.custom.yaml
  >    - yitian_26Keys.schema.yaml

- 執行 **重新部署** ，即可在選單(F4)內找到該輸入法
	- Windows: 從開始選單選擇 "重新部署";或當開啓右下工具列看到輸入法Icon時，對Icon點右鍵選擇""重新佈署"
	- Linux : 點輸入法狀態欄（或IBus菜單）上的 ⟲ (Deploy) 按鈕
	  > 如果是用Gnome desktop可以到Gnome Extension安裝[**Input Method Panel**](https://extensions.gnome.org/extension/261/kimpanel/)
	- MacOS: 在系統語言文字選單中選擇 "重新佈署""
- `essay-zh-hant-mc.txt` 是引用至 洋蔥輸入法 
  > 20240620 停用預設八股文依賴, 改用洋蔥輸入法提供八股文

- 簡繁轉換需安裝opencc才可使用



- 鍵位圖

  ![倚天鍵位](https://user-images.githubusercontent.com/33840759/129006031-ba7e1b72-7a5f-4d84-8bf8-8fd45d92310d.jpg)

