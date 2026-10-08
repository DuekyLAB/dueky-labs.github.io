# Dueky Labs — Development Rules (`RULES.md`)

이 문서는 **Dueky Labs** 공식 웹사이트 및 포트폴리오의 일관성, 유지보수성, 가벼운 배포 환경을 보장하기 위한 핵심 개발 규정입니다.

---

### 1. Single Source of Truth
- 모든 뷰와 레이아웃은 단일 `index.html` 파일 내에서 관리합니다.
- 복잡한 번들러(Webpack, Vite 등)나 무거운 빌드 의존성을 배제하고, GitHub Pages 및 정적 호스팅 환경에서 즉시 서비스될 수 있는 구조를 유지합니다.

### 2. Mobile-First & Responsive
- 모바일 디스플레이를 기본으로 설계한 뒤 태블릿 및 데스크톱으로 확장합니다.
- Tailwind CSS의 반응형 브레이크포인트(`sm: 640px`, `md: 768px`, `lg: 1024px`, `xl: 1280px`)를 엄격히 준수하여 모든 화면비에서 최적화된 레이아웃을 제공합니다.

### 3. Zero-Config Maintenance
- 복잡한 설정 없이 브라우저에서 바로 로드 가능한 형태를 유지하며, 인라인/하드코딩된 값의 중복을 지양합니다.
- HTML5 표준 시맨틱 태그(`<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`, `<article>` 등)를 엄격하게 사용하여 접근성과 SEO 최적화를 보장합니다.

### 4. Documentation
- 프로젝트 구조 변경, 디자인 개편, 피처 추가 및 릴리스 상태 업데이트 시 반드시 `LOG.md`에 타임스탬프와 변경 요약을 누적 기록합니다.
