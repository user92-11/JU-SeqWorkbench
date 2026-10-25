# JU SeqWorkbench Alpha 0.1.1-alpha.1 — Windows x64

**Release tag:** `v0.1.1-alpha.1`  
**Channel:** Pre-release / 연구용 시험판  
**Platform:** Windows x64  
**Package:** `JU_SeqWorkbench_Alpha_0.1.1-alpha.1_Windows_x64.zip`

> Download the application ZIP from the [published GitHub Release](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.1-alpha.1) **Assets**. The automatically generated **Source code** ZIP/tar.gz files contain only this public documentation repository, **not** the JU SeqWorkbench application.

## English

### What's improved in Alpha 0.1.1

- Improved FASTA **Open/Import** stability and support for BioEdit-style `~` gap characters.
- Fixed residual highlighting after changing or clearing an ID selection.
- Improved **View NT/RNA/AA** display transitions and preservation of the **AA Working** state.
- Improved Point/Similarity analysis linkage with the viewer and result image-saving behavior.
- Improved AA Marker behavior and shared CSV export workflows.
- Refined Korean/English UI messages.
- Fixed Qt and bundled-module loading issues associated with long Windows paths.

This is a patch to the existing Alpha workflows, **not** the Beta or a feature-complete release.

### Install and run

1. Download the Windows x64 ZIP listed above from the Release **Assets**.
2. Verify its SHA-256 against the checksum below or the corresponding `_SHA256.txt` asset.
3. Extract the entire ZIP into a new folder; do not run the executable inside the archive.
4. Run the program and consult the included Korean/English user guides and third-party notices.
5. External MSA requires a **separately installed and configured MAFFT**. MAFFT is not bundled.

### Package integrity

- **ZIP SHA-256 (GitHub asset digest):** `ed1a3c8e99ad519637f9d84595d90375140aa9d5e9ba631f606c0e6a5e9fd9c1`
- **Previous version:** [Alpha 0.1.0-alpha.1](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1) remains available.

*The SHA-256 above matches the digest published by GitHub for the uploaded ZIP. For independent verification, calculate the downloaded ZIP's hash locally. If checking against the text asset, ensure the filename inside that text matches the renamed ZIP.*

### Evaluation notice

This is experimental research software and has **not been validated for clinical or diagnostic use**. Do not use it as the sole basis for clinical, diagnostic, regulatory or official decisions. Back up original data and independently verify important findings. Some features remain in development and performance can vary by dataset and PC environment.

Please report problems through [JU-works Issues](https://github.com/user92-11/JU-works/issues) using synthetic or redacted examples; **do not upload unpublished sequences, confidential data or personal information** to public issues.

## 한국어

### Alpha 0.1.1 주요 개선 사항

- FASTA **Open/Import** 안정화 및 BioEdit 방식의 `~` gap 문자 지원.
- ID 선택 변경·해제 후 남는 하이라이트 잔상 수정.
- **View NT/RNA/AA** 표시 전환 및 **AA Working** 상태 보존 개선.
- Point/Similarity 분석 결과와 Viewer의 연동 및 결과 이미지 저장 동작 개선.
- AA Marker 동작과 공통 CSV 저장 흐름 개선.
- 한국어/영어 UI 안내 메시지 보완.
- Windows 긴 경로에서 발생하는 Qt 및 번들 모듈 로딩 문제 수정.

기존 Alpha 기능을 유지하면서 안정성을 개선한 패치이며, **Beta 또는 기능 완성판은 아닙니다.**

### 설치 및 실행

1. GitHub Release **Assets**에서 위 Windows x64 ZIP을 다운로드합니다.
2. 아래 SHA-256 또는 함께 게시된 `.sha256` 파일로 무결성을 확인합니다.
3. ZIP 전체를 새 폴더에 압축 해제합니다. ZIP 내부에서 직접 실행하지 마세요.
4. 프로그램을 실행하고 한국어/영어 사용 설명서와 제3자 라이선스 고지를 확인합니다.
5. 외부 MSA 기능은 별도 설치·설정한 **MAFFT**가 필요합니다. MAFFT는 동봉되지 않습니다.

### 패키지 무결성

- **ZIP SHA-256 (GitHub Asset 기준):** `ed1a3c8e99ad519637f9d84595d90375140aa9d5e9ba631f606c0e6a5e9fd9c1`
- **이전 버전:** [Alpha 0.1.0-alpha.1](https://github.com/user92-11/JU-SeqWorkbench/releases/tag/v0.1.0-alpha.1)은 별도로 보존됩니다.

*위 값은 업로드된 ZIP에 대해 GitHub가 제공하는 SHA-256과 일치합니다. 다운로드 후 로컬에서 독립적으로 확인할 수 있습니다. TXT를 이용해 파일명까지 검사할 때는 내부에 기록된 이름이 변경된 ZIP 파일명과 일치하는지 확인하세요.*

### 시험판 안내

JU SeqWorkbench Alpha는 연구 작업 흐름 검증용 시험판이며 **임상·진단용으로 검증되지 않았습니다**. 임상·진단·규제·공식 판단에 단독으로 사용하지 마세요. 원본 데이터를 백업하고 중요한 분석 결과는 독립적으로 확인하세요. 일부 기능은 개발 중이며 PC 환경과 데이터에 따라 성능 및 동작이 달라질 수 있습니다.

오류나 의견은 [JU-works Issues](https://github.com/user92-11/JU-works/issues)로 알려주세요. 공개 이슈에 미공개 서열, 기관 내부 자료 또는 개인정보를 올리지 말고 합성·비식별 예시를 사용해 주세요.

---

**Distribution policy:** This public repository contains release documentation and packaged builds only. Proprietary JU SeqWorkbench application source code is **not** published here. Third-party components remain subject to their respective licenses and bundled notices.
