# JU SeqWorkbench Alpha 0.1.0 — Release Notes
**Planned tag:** `v0.1.0-alpha.1` · **Platform:** Windows x64 · **Channel:** Pre-release (evaluation)

> **Published / 배포 완료 (2026-10-12):** Download the Windows x64 program ZIP from the **Assets** section of [Alpha 0.1.0 Pre-release](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1). The automatically generated GitHub source archives contain documentation only, not the proprietary application.


## English

### About
JU SeqWorkbench is a Windows research desktop application for reviewing Sanger/FASTA sequences, editing aligned NT/AA data, and visualizing site- and region-level variation patterns.

### Highlights
- FASTA import and AB1 chromatogram viewing
- NT/AA display and conversion; View/Edit, OVR/INS, Color/Dot modes
- ID/BODY/COLUMN selection, multi-highlighting, clipboard editing, Undo/Redo
- Point and Region Visualization; Similarity Clustering
- AA Marker Classification and ID/Name Grouping
- Supported FASTA/CSV and PNG/JPG/PDF/SVG exports
- Optional external MSA through a separately installed **MAFFT**

### Installation
1. Download the Windows x64 ZIP from the [Alpha 0.1.0 GitHub Release](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1) **Assets**.
2. Extract the entire ZIP to a new folder (do not run directly inside the archive).
3. Launch `JU SeqWorkbench Alpha.exe`. Python installation is not required.
4. Read the included English/Korean guides and third-party notices.

### Limitations and caution
- **Alpha testing build.** Not intended as the sole basis for clinical, diagnostic, regulatory, or official decisions. Independently verify research findings and back up source data.
- With AA Marker Stop handling set to **Truncate**, residues after the first `*` are excluded from classification. Choose **Keep** when scientifically appropriate to consider downstream positions.
- NT↔AA view-conversion time may vary by dataset and hardware.
- External aligners are not bundled. **MAFFT** requires separate installation; **Clustal Omega** is disabled in this Alpha.
- Planned features such as Sequence Management, phylogenetic trees, and annotation layers are not included.
- The executable may be unsigned; verify the source and SHA-256 before running.
- Data is processed locally unless you independently share or upload it elsewhere.

### Published artifact integrity (RC2-validated)
- ZIP: `JU_SeqWorkbench_Alpha_Windows_x64.zip`
- SHA-256: `FE280649650F91F893682DF25D2AEFF666B966A7EDE0E90209058B5F8D16B289`
- The unused Qt PDF runtime components were removed; required third-party license notices remain bundled.

### Feedback
- [Bug reports / feature requests](https://github.com/user92-11/JU-works/issues)
- [Questions / ideas](https://github.com/user92-11/JU-works/discussions)
- [Project page](https://user92-11.github.io/JU-works/)

## 한국어

### 소개
JU SeqWorkbench는 Sanger/FASTA 기반 서열을 열고, 정렬된 NT/AA 서열을 검토·편집하며, 변이·위치·구간 패턴을 시각화하는 Windows 데스크톱 연구 도구입니다.

### 주요 기능
- FASTA 서열 가져오기와 AB1 크로마토그램 확인
- NT/AA 서열 표시·변환, View/Edit, OVR/INS, Color/Dot 모드
- ID·BODY·COLUMN 선택, 다중 하이라이트, 복사·붙여넣기, Undo/Redo
- Point 및 Region Visualization, Similarity Clustering
- AA Marker Classification, ID/Name Grouping
- FASTA·CSV 및 PNG/JPG/PDF/SVG 등 지원 형식 내보내기
- 사용자가 별도 설치한 **MAFFT**를 이용한 외부 MSA 연동

### 설치 및 사용
1. [GitHub Alpha 0.1.0 Release](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1)의 **Assets**에서 Windows x64 ZIP 파일을 받습니다.
2. ZIP 전체를 새 폴더에 압축 해제합니다. ZIP 내부에서 EXE를 직접 실행하지 마세요.
3. 압축 해제한 폴더의 `JU SeqWorkbench Alpha.exe`를 실행합니다. Python 별도 설치는 필요하지 않습니다.
4. 앱에 포함된 한국어/영어 사용자 가이드와 제3자 라이선스 고지를 확인하세요.

### 알아둘 사항
- **시험판입니다.** 연구 작업흐름 검증용이며, 임상 진단·규제 판단·공식 보고에 단독으로 사용하지 마세요. 분석 결과를 독립적으로 확인하고 원본 파일을 백업하세요.
- AA Marker에서 Stop handling이 **Truncate**이면 첫 번째 `*` 이후 서열은 분류 입력에서 제외됩니다. 뒤쪽 마커까지 평가하려면 목적에 맞게 **Keep** 옵션을 선택하세요.
- NT↔AA 변환 시간은 데이터 크기 및 PC 환경에 따라 달라질 수 있습니다.
- 외부 정렬 도구는 패키지에 포함되지 않습니다. **MAFFT**는 별도 설치/설정이 필요하며, **Clustal Omega** 선택은 이 Alpha에서 비활성화되어 있습니다.
- 일부 계획된 기능(Sequence Management, 계통수·Annotation 계층 등)은 포함되지 않습니다.
- Windows 실행 파일은 코드 서명되지 않았을 수 있으니 다운로드 출처와 SHA-256을 확인하세요.
- 파일은 로컬에서 처리됩니다. 사용자가 별도로 외부에 업로드하거나 공유하는 경우는 제외합니다.

### 공개 배포 파일 및 RC2 검증 정보
- Windows RC2 ZIP: `JU_SeqWorkbench_Alpha_Windows_x64.zip`
- ZIP SHA-256: `FE280649650F91F893682DF25D2AEFF666B966A7EDE0E90209058B5F8D16B289`
- Build provenance: application source `a23a3c7`; packaging exclusion commit `5b67fd7`.
- ZIP에는 `Qt6Pdf.dll` 및 `qpdf.dll`이 포함되지 않으며, 필수 제3자 라이선스 고지 파일은 포함됩니다.

### 피드백
- 버그·기능 요청: [JU-works Issues](https://github.com/user92-11/JU-works/issues)
- 질문·아이디어: [JU-works Discussions](https://github.com/user92-11/JU-works/discussions)
- 프로젝트 소개: [JU-works](https://user92-11.github.io/JU-works/)

---

**Software distribution policy:** This public repository is for release information and downloadable binaries, not the proprietary JU SeqWorkbench Python source. Third-party components are governed by their respective licenses and included notices.
