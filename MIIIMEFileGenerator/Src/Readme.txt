========================================================================
        MIIIME File Generator (MFG)
========================================================================

A small GUI utility that batch-creates or removes placeholder files
(e.g. .gitkeep) across a directory tree, allowing empty folders to be
tracked and committed to GitHub.

빈 폴더를 GitHub에 커밋할 수 있도록 디렉토리 트리 전체에
플레이스홀더 파일(예: .gitkeep)을 일괄 생성하거나 제거합니다. 

========================================================================
[Features / 기능]
========================================================================

Create Mode
- Generates a specified file (default: .gitkeep) in target folders.
- Scope : All Folders — applies to every folder in the tree / Leaf Folders — applies only to folders with no subfolders.
- State : Always — creates regardless of existing contents / Empty Only — skips folders that already contain files or subfolders.

생성 모드
- 지정한 파일(기본값: .gitkeep)을 대상 폴더에 일괄 생성.
- 범위 : All Folders — 트리 전체 적용 / Leaf Folders — 하위 폴더가 없는 말단 폴더에만 적용.
- 조건 : Always — 기존 내용에 무관하게 생성 / Empty Only — 파일·하위 폴더가 없는 빈 폴더에만 생성.

Delete Mode
- Removes the specified file from every folder in the tree.
- Scope and content settings are fixed; only the filename is referenced.

삭제 모드
- 트리 전체에서 지정한 파일을 일괄 제거.
- 범위 및 조건 설정은 고정되며 파일명만 참조.

========================================================================
[Usage / 사용법]
========================================================================

  1. Run MIIIMEFileGenerator.exe.
     MIIIMEFileGenerator.exe 실행.

  2. Enter the target folder path, or drag-and-drop a folder.
     대상 폴더 경로를 입력하거나 드래그앤드롭.

  3. Set the filename, scope, and condition.
     파일명, 범위, 조건 설정.

  4. Click Run and confirm the operation summary dialog.
     Run 클릭 후 작업 요약 다이얼로그 확인.

  Settings are saved to MIIIMEFileGenerator.ini automatically.
  설정값은 MIIIMEFileGenerator.ini에 자동 저장됨.

========================================================================
[Localization / 다국어]
========================================================================

  Place locale files under Loc\<lang>.ini to override all UI strings.
  Loc\<lang>.ini에 로케일 파일을 배치하면 UI 문자열을 재정의할 수 있음.

========================================================================

This program was created with AutoIt. Some antivirus programs may
incorrectly detect it as a virus.
본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 오진할 수 있습니다.

========================================================================
[Disclaimer / 면책]
========================================================================

Provided "AS IS", without warranty.
This is a private project. No technical support is provided.

본 프로그램은 "있는 그대로" 제공되며, 사용 중 발생하는 문제에 대해
제작자는 책임을 지지 않습니다. 기술 지원은 제공되지 않습니다.

Developer  : MIIIME
Website    : https://www.miiime.com
GitHub     : @miiime6248
Update     : 2026-02-14
