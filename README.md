# Unitree G1 Web Simulator

브라우저에서 바로 실행되는 Unitree G1 로봇 시뮬레이터입니다. 설치 없이 파일 업로드만으로 동작합니다.

A browser-based Unitree G1 robot simulator. No installation needed — just upload files and go.

**🔗 Live Demo → [leeyunjai82.github.io/unitree-g1-simulator](https://leeyunjai82.github.io/unitree-g1-simulator/)**

---

## 사용법 (How to Use)

**① 파일 받기 (Download files)**

이 저장소에서 두 파일을 다운로드하세요.

Download these two files from this repository:

- [`g1_29dof_rev_1_0.urdf`](./g1_29dof_rev_1_0.urdf)
- [`meshes.zip`](./meshes.zip) → 압축 해제 후 사용 (unzip before use)

**② 시뮬레이터 열기 (Open the simulator)**

위 Live Demo 링크를 브라우저에서 여세요.

Open the Live Demo link in your browser.

**③ 파일 업로드 (Upload files)**

| 버튼 | 선택할 파일 | Button | File to select |
|------|------------|--------|----------------|
| URDF 파일 선택 | `g1_29dof_rev_1_0.urdf` | Select URDF | `g1_29dof_rev_1_0.urdf` |
| STL 다중 선택 | `meshes/` 폴더 안 STL 파일 전체 | Select STLs | All STL files inside `meshes/` folder |

**④ 로드 (Load)**

`로드 (Load)` 버튼 클릭 → 로봇 모델이 3D로 표시됩니다.

Click the `로드 (Load)` button → the robot appears in 3D.

---

## 주요 기능 (Features)

| 기능 | Feature |
|------|---------|
| 3D 뷰어 (회전 / 이동 / 줌) | 3D viewer — rotate / pan / zoom |
| 관절 슬라이더 (URDF limit 자동 반영) | Joint sliders with URDF limits |
| 관절 그룹 접기/펴기 | Collapsible joint groups |
| 관절 검색 | Joint search filter |
| 와이어프레임 / 좌표축 토글 | Wireframe / axis toggle |
| 메시 클릭 → 관절 하이라이트 | Click mesh → highlight related joints |
| 포즈 저장 / 불러오기 (JSON) | Save / load pose as JSON |
| 타임라인 모션 에디터 | Timeline-based motion editor |
| 키프레임 추가 / 드래그 / 재생 | Add keyframes, drag to reposition, playback |
| 모션 저장 / 불러오기 (JSON) | Save / load motion as JSON |
| 스크린샷 | Screenshot export |

---

## 조작법 (Controls)

| 조작 | 기능 | Control | Action |
|------|------|---------|--------|
| 좌클릭 드래그 | 회전 | Left drag | Rotate |
| 우클릭 드래그 | 이동 | Right drag | Pan |
| 휠 스크롤 | 줌 | Scroll wheel | Zoom |
| 타임라인 클릭 | 시간 이동 | Click timeline | Seek |
| 키프레임 드래그 | 시간 조정 | Drag keyframe | Reposition |
| 타임라인 더블클릭 | 키프레임 추가 | Double-click timeline | Add keyframe |

---

## 기술 스택 (Built With)

- [Three.js r128](https://threejs.org/) — 3D rendering
- Pure HTML / JavaScript — no frameworks, no server
