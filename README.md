# URDF Web Simulator

브라우저에서 바로 실행되는 URDF 로봇 시뮬레이터입니다. 설치 없이 URDF + STL 파일 업로드만으로 동작합니다.

A browser-based URDF robot simulator. No installation needed — just upload your URDF and STL files.

**🔗 Live Demo → [leeyunjai82.github.io/unitree-g1-simulator](https://leeyunjai82.github.io/unitree-g1-simulator/)**

---

<video src="test.mp4" controls width="100%"></video>

---

## 주요 기능 (Features)

- 3D 뷰어 (회전 / 이동 / 줌) — 3D viewer (rotate / pan / zoom)
- 관절 슬라이더 (URDF limit 자동 반영) — Joint sliders with URDF limits
- 포즈 저장 / 불러오기 — Save / load pose as JSON
- 타임라인 모션 에디터 — Timeline-based motion editor
- 와이어프레임 / 좌표축 토글 — Wireframe / axis toggle
- 스크린샷 — Screenshot export

## 사용법 (How to Use)

1. Live Demo 링크를 브라우저에서 열기
2. URDF 파일 선택
3. STL 파일 다중 선택 (`meshes/` 폴더 전체)
4. `로드 (Load)` 버튼 클릭

## 기술 스택 (Built With)

- [Three.js r128](https://threejs.org/)
- Pure HTML / JavaScript
