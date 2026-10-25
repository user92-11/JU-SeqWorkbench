# JU SeqWorkbench

**Sequence analysis and visualization for research**  
Sanger/FASTA → AB1 review → alignment → NT/AA editing → site/region analysis → export

[한국어](#한국어) · [English](#english) · [Alpha 0.1.1 patch notes](./RELEASE_NOTES_v0.1.1-alpha.1.md) · [Alpha 0.1.0 notes](./RELEASE_NOTES_v0.1.0-alpha.1.md) · [Project website](https://user92-11.github.io/JU-works/)

> **Alpha 0.1.1 patch / 패치 배포 준비 중:** [Bilingual 0.1.1 Release Notes / 한·영 변경 사항](./RELEASE_NOTES_v0.1.1-alpha.1.md) are ready. The new download will be linked **only after** the pre-release and final ZIP/checksum assets are published and verified. Until then, **Alpha 0.1.0 remains the current download**. / 0.1.1 릴리스 파일 업로드와 검증이 끝나기 전까지 현재 다운로드는 0.1.0입니다.

> **Released / 배포 완료 (2026-10-12):** [Download JU SeqWorkbench Alpha 0.1.0 — Windows x64](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1) from **Assets**. The actual application ZIP is `JU_SeqWorkbench_Alpha_0.1.0_Windows_x64.zip`; do not select the automatically generated GitHub source archives.

### Alpha screenshot — Point results ↔ alignment viewer

![JU SeqWorkbench Alpha 0.1.0 Point mutation results table linked to highlighted sequences and positions in the CPV-2 alignment](https://raw.githubusercontent.com/user92-11/JU-works/main/assets/images/devlog/ju-point-linked-highlight-cpv2-alpha010.png)

*Select a mutation result to inspect the corresponding sequences and alignment position. CPV-2 example from the actual Alpha 0.1.0 interface.*

*변이 결과를 선택하면 해당 서열과 정렬 위치가 Viewer에 연동되어 표시됩니다. 실제 Alpha 0.1.0의 CPV-2 분석 예시입니다.*

[View the associated Point sequence logo and detailed workflow / Point Logo Plot 및 상세 설명](https://user92-11.github.io/JU-works/devlog/05-visualization-and-inspection/)

## English

**JU SeqWorkbench** is a **Windows desktop research tool** for reviewing Sanger/FASTA data, editing aligned NT/AA sequences, and inspecting position-, region-, and group-level variation patterns.

### Features

- FASTA import and AB1 chromatogram inspection
- NT/AA sequence viewing and editing, View/Edit, OVR/INS, Color/Dot
- ID/BODY/COLUMN selection, persistent highlights, clipboard operations and Undo/Redo
- Point/Region Visualization and Similarity Clustering
- AA Marker Classification and ID/Name Grouping
- Supported FASTA/CSV and PNG/JPG/PDF/SVG exports
- External alignment via a separately installed **MAFFT**

### Download and run

Download the **Windows x64 ZIP** from [**Alpha 0.1.0 Release**](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1), extract the entire archive to a new folder, and launch `JU SeqWorkbench Alpha.exe`. **No Python installation is required.**

Korean and English user guides are included in the distribution. [Release notes and checksum](./RELEASE_NOTES_v0.1.0-alpha.1.md)

### Alpha notice

This is an **evaluation build for research workflows**, not a standalone basis for clinical, diagnostic, regulatory, or official decisions. Verify important results independently and back up original data.

Some functions are planned or limited. Performance depends on dataset and hardware. External aligners are **not bundled**, and Clustal Omega is unavailable in this Alpha.

### Feedback

If you encounter a bug or have suggestions while evaluating this Alpha, please share them through the links below. Include the JU version, Windows version, steps to reproduce, and any error message when relevant. Your feedback helps improve compatibility, stability, and usability. **GitHub Issues are public: do not upload unpublished sequences, personal information, or confidential research data.** Use a synthetic or redacted example instead.

- [Bugs and feature requests — GitHub Issues](https://github.com/user92-11/JU-works/issues)
- [Questions and ideas — GitHub Discussions](https://github.com/user92-11/JU-works/discussions)
- [JU-works development website](https://user92-11.github.io/JU-works/)

## 한국어

**JU SeqWorkbench**는 Sanger/FASTA 데이터를 바탕으로 서열을 검토하고, 정렬된 NT/AA 데이터를 편집하며, 위치·구간·그룹별 변이 패턴을 확인하는 **Windows 데스크톱 연구 프로그램**입니다.

### 주요 기능

- FASTA 가져오기, AB1 크로마토그램 열기·확인
- NT/AA 뷰어 및 편집, View/Edit·OVR/INS·Color/Dot 모드
- ID/BODY/COLUMN 선택, 다중 하이라이트, 복사·붙여넣기, Undo/Redo
- Point/Region Visualization, Similarity Clustering
- AA Marker Classification, ID/Name Grouping
- FASTA/CSV 및 이미지(PNG/JPG/PDF/SVG) 등 지원 형식 내보내기
- 별도 설치한 **MAFFT**를 통한 외부 MSA

### 다운로드 및 실행

[**Alpha 0.1.0 GitHub Release**](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1) 페이지의 Assets에서 **Windows x64 ZIP**을 다운로드할 수 있습니다. ZIP 전체를 새 폴더에 압축 해제하고 `JU SeqWorkbench Alpha.exe`를 실행하면 됩니다. **Python 설치는 필요하지 않습니다.**

기본 사용법과 세부 기능은 배포 패키지에 포함된 **한국어/영어 사용자 가이드**를 참고하세요. [Alpha 릴리스 안내 및 SHA-256](./RELEASE_NOTES_v0.1.0-alpha.1.md)

### 시험판 안내

Alpha는 연구 작업흐름의 검증과 피드백을 위한 시험판입니다. **임상·진단·규제·공식 판단을 위한 단독 근거로 사용하지 마세요.** 중요한 데이터는 백업하고 분석 결과를 독립적으로 검증해 주세요.

일부 기능은 개발 중이며, 대형 데이터에서 처리 시간이 PC 환경에 따라 달라질 수 있습니다. 외부 정렬 도구는 동봉되지 않으며, **Clustal Omega는 이번 Alpha에서 비활성화**되어 있습니다.

### 문의 및 피드백

Alpha를 사용하다가 오류를 발견하거나 개선 의견이 있다면 아래 링크로 알려주세요. 가능하면 JU 버전, Windows 버전, 오류 재현 단계 및 오류 메시지를 함께 적어주세요. 호환성·안정성·사용성 개선에 도움이 됩니다. **GitHub Issues는 공개되므로 미공개 연구 서열, 개인정보, 기관 내부 자료는 업로드하지 마세요.** 필요한 경우 합성 데이터나 비식별화한 예시를 사용해 주세요.

- [버그 제보·기능 요청 — GitHub Issues](https://github.com/user92-11/JU-works/issues)
- [질문·의견·아이디어 — GitHub Discussions](https://github.com/user92-11/JU-works/discussions)
- [JU-works 개발 홈페이지](https://user92-11.github.io/JU-works/)

---

### Distribution and third-party notices

**JU SeqWorkbench application source code is proprietary and is not published in this repository.** This repository contains public release documentation and will host downloadable builds. The automatically generated GitHub source archives refer only to this public repository, **not** the proprietary application source or the Windows executable.

Third-party libraries retain their respective licenses. Applicable copyright, LGPL/GPL and other third-party license notices are included with the Windows distribution. No open-source license for the proprietary application is granted by the absence of a repository LICENSE file.
