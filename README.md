# Shiina Taki's Decameron — English / Korean / Japanese Patch

Version 1.2.0

---

## English

### What this patch does

- Adds English, Korean, and Japanese localization modes.
- Displays the original Chinese line above the selected translation.
- Covers story text, speaker names, choices, UI text, backlog, and seven aphorism cards.
- Does not include translations for the main title screen, as its text appears to be embedded in images.
- Includes a local proofreading editor that can save corrections directly to JSON.

### Easy installation and language switching

1. In Steam, right-click the game and select **Manage → Browse local files**.
2. Open the inner folder containing:

```text
鼓手余命十日谭.exe
index.html
asset
```

3. Copy the entire `Localization_Patch` folder into that folder.
4. Open `Localization_Patch` and double-click the language you want:

```text
01_Install_or_Switch_English.cmd
02_한국어_설치_전환.cmd
03_日本語_インストール_切替.cmd
```

The same files are used both for first installation and later language switching.

5. Fully exit and restart the game. Returning only to the title screen is not enough.

### Local proofreading editor

Double-click:

```text
04_Open_Review_Tool.cmd
```

Python 3.10 or newer is required. The editor opens in your browser and is available only on `127.0.0.1`; it is not exposed to the internet.

The editor interface can be switched independently between:

```text
中文 / English / 日本語 / 한국어
```

You can separately select English, Korean, or Japanese as the text being reviewed. The editor supports story text, choices, speaker names, and aphorism captions. Saving automatically updates the canonical JSON, context workspace, runtime dictionary, and legacy redirects. A complete backup is created on every launch.

### Uninstall

Double-click:

```text
05_Uninstall_Patch.cmd
```

Save data is not removed.

---

## 한국어

### 패치 기능

- 영어, 한국어, 일본어 번역을 지원합니다.
- 중국어 원문을 위에, 선택한 번역을 아래에 표시합니다.
- 시나리오, 화자 이름, 선택지, UI, 백로그, 잠언 카드 7장을 번역합니다.
- JSON에 직접 저장할 수 있는 로컬 교정 도구가 포함되어 있습니다.

### 간편 설치 및 언어 전환

1. Steam에서 게임을 우클릭하고 **관리 → 로컬 파일 보기**를 선택합니다.
2. 다음 파일이 있는 안쪽 게임 폴더를 엽니다.

```text
鼓手余命十日谭.exe
index.html
asset
```

3. `Localization_Patch` 폴더 전체를 이곳에 복사합니다.
4. `Localization_Patch` 폴더를 열고 원하는 언어 파일을 더블클릭합니다.

```text
01_Install_or_Switch_English.cmd
02_한국어_설치_전환.cmd
03_日本語_インストール_切替.cmd
```

같은 파일로 처음 설치하거나 나중에 언어를 바꿀 수 있습니다.

5. 게임을 완전히 종료하고 다시 실행합니다. 타이틀 화면으로만 돌아가서는 적용되지 않습니다.

### 로컬 교정 도구

다음 파일을 더블클릭합니다.

```text
04_Open_Review_Tool.cmd
```

Python 3.10 이상이 필요합니다. 인터페이스 언어는 중국어, 영어, 일본어, 한국어 중에서 교정 대상 언어와 별도로 선택할 수 있습니다. 저장하면 JSON, 문맥 작업 파일, 실행용 사전이 함께 갱신되며 시작할 때마다 백업을 만듭니다.

### 제거

```text
05_Uninstall_Patch.cmd
```

저장 데이터는 삭제되지 않습니다.

---

## 日本語

### パッチの内容

- 英語・韓国語・日本語に対応しています。
- 中国語原文を上段、選択した訳文を下段に表示します。
- シナリオ、話者名、選択肢、UI、バックログ、七枚の箴言カードを翻訳します。
- JSONへ直接保存できるローカル校正ツールを同梱しています。

### 簡単インストール・言語切り替え

1. Steamでゲームを右クリックし、**管理 → ローカルファイルを閲覧**を選びます。
2. 次のファイルがある内側のゲームフォルダーを開きます。

```text
鼓手余命十日谭.exe
index.html
asset
```

3. `Localization_Patch` フォルダーを丸ごとコピーします。
4. `Localization_Patch` を開き、使いたい言語のファイルをダブルクリックします。

```text
01_Install_or_Switch_English.cmd
02_한국어_설치_전환.cmd
03_日本語_インストール_切替.cmd
```

初回インストールと、後からの言語切り替えに同じファイルを使えます。

5. ゲームを完全に終了してから再起動してください。タイトル画面へ戻るだけでは反映されません。

### ローカル校正ツール

次のファイルをダブルクリックします。

```text
04_Open_Review_Tool.cmd
```

Python 3.10以降が必要です。画面表示は中国語・英語・日本語・韓国語から、校正対象の言語とは別に選べます。保存するとJSON、文脈ワークスペース、実行用辞書が同期され、起動時にバックアップが作成されます。

### アンインストール

```text
05_Uninstall_Patch.cmd
```

セーブデータは削除されません。

---

## 中文

### 补丁内容

- 提供英语、韩语和日语补丁。
- 游戏内采用“中文原文在上、所选译文在下”的双语显示。
- 覆盖剧情、姓名栏、选项、界面、历史记录和七张箴言字幕。
- 附带能够直接保存到 JSON 的本地校对工具。

### 最简单的安装和切换方法

1. 在 Steam 中右键游戏，选择 **管理 → 浏览本地文件**。
2. 进入同时包含以下内容的内层游戏目录：

```text
鼓手余命十日谭.exe
index.html
asset
```

3. 把整个 `Localization_Patch` 文件夹复制到这里。
4. 打开 `Localization_Patch`，双击需要的语言：

```text
01_Install_or_Switch_English.cmd
02_한국어_설치_전환.cmd
03_日本語_インストール_切替.cmd
```

首次安装和以后切换语言都使用同一个文件。

5. 完全退出并重新启动游戏。只退回标题页不会刷新补丁。

### 本地校对工具

双击：

```text
04_Open_Review_Tool.cmd
```

需要 Python 3.10 或更高版本。校对台只在本机 `127.0.0.1` 运行，不会向互联网开放。

校对台界面可以独立切换为：

```text
中文 / English / 日本語 / 한국어
```

被校对的文本语言则可以另外选择英语、韩语或日语。校对台可以修改剧情、选项、姓名栏和箴言字幕。点击保存后会同步主稿、上下文、游戏运行词典和旧文本重定向；每次启动都会自动备份。

### 卸载

双击：

```text
05_Uninstall_Patch.cmd
```

卸载不会删除游戏存档。

---

## Notes

- The development team has kindly granted permission for this patch to be released as a fan-made project.
- Audio, countdown videos, the final ED, and non-aphorism cutscenes are not modified.
- Source Han Sans JP/KR fonts are distributed under the SIL Open Font License. See `fonts/LICENSE-SourceHanSans.txt`.
- This package contains only patch files and the proofreading tool. It does not contain the game.

---

## Credits / Contact

weibo: **@大树_Taiki**  
AO3: **Taiki_Shuttle**
