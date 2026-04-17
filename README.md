# MIIIME File Generator (MFG)

![OS](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&style=flat-square)
[![Language](https://img.shields.io/badge/Language-AutoIt-orange?logo=autoit&style=flat-square)](https://www.autoitscript.com/site/)
![License](https://img.shields.io/badge/License-Freeware-lightgrey?style=flat-square)

<br>
<img width="559" height="136" alt="001" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Enhanced/Id/Neon/4b_136_1_G.png?raw=true" style="margin-top: 20px; margin-bottom: 20px;">
<br>

A small GUI utility that batch-creates or removes placeholder files (e.g. `.gitkeep`) across a directory tree,  
allowing empty folders to be tracked and committed to GitHub.

빈 폴더를 GitHub에 커밋할 수 있도록 디렉토리 트리 전체에 플레이스홀더 파일(예: `.gitkeep`)을  
일괄 생성하거나 제거하는 소형 GUI 유틸리티.

---

## Features / 기능

### Create Mode

- Generates a specified file (default: `.gitkeep`) in target folders.
- **Scope** : All Folders — applies to every folder in the tree / Leaf Folders — applies only to folders with no subfolders.
- **State** : Always — creates regardless of existing contents / Empty Only — skips folders that already contain files or subfolders.

### 생성 모드

- 지정한 파일(기본값: `.gitkeep`)을 대상 폴더에 일괄 생성.
- **범위** : All Folders — 트리 전체 적용 / Leaf Folders — 하위 폴더가 없는 말단 폴더에만 적용.
- **조건** : Always — 기존 내용에 무관하게 생성 / Empty Only — 파일·하위 폴더가 없는 빈 폴더에만 생성.

### Delete Mode

- Removes the specified file from every folder in the tree.
- Scope and content settings are fixed; only the filename is referenced.

### 삭제 모드

- 트리 전체에서 지정한 파일을 일괄 제거.
- 범위 및 조건 설정은 고정되며 파일명만 참조.

---

## Configuration / 설정

Settings are persisted to `MIIIMEFileGenerator.ini` on each run.  
실행 시 설정값이 `MIIIMEFileGenerator.ini`에 자동 저장됨.

| Parameter       | Section | Description                                          |
| --------------- | ------- | ---------------------------------------------------- |
| `FileName`      | General | Target filename / 대상 파일명 (default: `.gitkeep`)       |
| `FileContent`   | General | File content written on creation / 생성 시 기록할 파일 내용    |
| `OperationMode` | General | `CREATE` or `DELETE`                                 |
| `TargetScope`   | General | `1` = All Folders, `2` = Leaf Folders                |
| `TargetState`   | General | `1` = Always, `2` = Empty Folders Only (CREATE mode) |
| `TargetFolder`  | General | Last-used target directory / 마지막 사용 경로               |
| `Local`         | Options | UI locale (`En` / other) / UI 언어                     |

---

## Localization / 다국어

Place locale files under `Loc\<lang>.ini` to override all UI strings.  
`Loc\<lang>.ini`에 로케일 파일을 배치하면 모든 UI 문자열을 재정의할 수 있음.

```text
Loc/
 └─ Ko.ini    # Korean / 한국어 (example)
```

---

## Usage / 사용법

1. Run `MIIIMEFileGenerator.exe`.  
2. Enter (or drag-and-drop) the target folder path.  
3. Set the filename, scope, and condition.  
4. Click **Run** and confirm the operation summary dialog.

<br>

1. `MIIIMEFileGenerator.exe` 실행.  
2. 대상 폴더 경로 입력 또는 드래그앤드롭.  
3. 파일명, 범위, 조건 설정.  
4. **Run** 클릭 후 작업 요약 다이얼로그 확인.

---

## 🛡️ Security & Anti-virus Info

### https://www.virustotal.com/gui/file/bba6c594cf7e548390636543d8b8829a2f05eb1f8d775384580087bc808974bb?nocache=1

| Status             | Details                                                                        |
|:------------------ |:------------------------------------------------------------------------------ |
| **Major Vendors**  | **Clean** (Passed by AhnLab V3, Kaspersky, Microsoft, Avast, ESET, etc.)       |
| **Detection Rate** | **10 / 72** (Mostly Heuristic/Generic/Trojan-type flags)                       |
| **Integrity**      | The source code is transparently available for verification in this repository |

> This launcher was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.  
> 본 런처는 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다. 

**File Checksum (SHA-256) :** `bba6c594cf7e548390636543d8b8829a2f05eb1f8d775384580087bc808974bb`

---

## Disclaimer

Provided **"AS IS"**, without warranty.  
This is a **private project**. No technical support is provided.

본 프로그램은 **"있는 그대로"** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.  
기술 지원은 제공되지 않습니다.

---

## Project Information

**Developer** : MIIIME  
**Website** : https://www.miiime.com  
**GitHub** : [@miiime6248](https://github.com/miiime6248)  
**Last Update** : 2026-02-14  

<br>
<img width="64" height="64" alt="002" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Brutal/Logo/Neon/4b_Mium_64_0_G.png?raw=true">  
<br>
<br>
<br>
