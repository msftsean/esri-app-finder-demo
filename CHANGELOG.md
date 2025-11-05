# Changelog

All notable changes to the ESRI App Finder & Builder Assistant will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned for v1.1.0
- Error handling & graceful degradation implementation
- WCAG 2.1 AA accessibility compliance
- Testing coverage (target 80%+)
- Azure OpenAI production integration
- ESRI Living Atlas API production integration

## [1.0.0] - 2025-11-05

### Added
- Initial release of ESRI App Finder & Builder Assistant
- Conversational AI chat interface with natural language processing
- Interactive ESRI map using ArcGIS Maps SDK 4.31
- Living Atlas dataset search functionality
- App recommendation engine for 12 ESRI configurable applications
- Real-time streaming chat responses (mocked)
- App preview and configuration interface
- Responsive design supporting desktop and mobile
- Zustand state management for global app state
- Azure Functions backend with Node.js v4 programming model
- TypeScript strict mode across frontend and backend
- Tailwind CSS 3.4.18 styling system
- GitHub Spec Kit constitutional framework (9 articles)

### Documentation
- Comprehensive API specification (4 endpoints)
- Frontend component specification (11 components)
- Error handling & graceful degradation specification
- Codebase analysis (75% implementation complete)
- Specification development plan (10 documents)
- Constitutional compliance review

### Technical Stack
- **Frontend:** React 19.1.1, TypeScript 5.9.3, Vite 7.1.7
- **Backend:** Azure Functions v4, Node.js 20, TypeScript 5.9.3
- **State:** Zustand 5.0.8
- **Styling:** Tailwind CSS 3.4.18
- **Maps:** ArcGIS Maps SDK 4.31

### Known Issues
- Azure OpenAI integration mocked (not connected to production)
- ESRI Living Atlas API mocked (not connected to production)
- Test coverage below 20% (target: 80%)
- Three constitutional violations:
  - Article VII: Graceful Degradation (missing error handling)
  - Article VIII: Accessibility (no WCAG 2.1 AA compliance)
  - Article IX: Testing & Observability (insufficient coverage)

### Infrastructure
- Frontend dev server: http://localhost:5175
- Backend dev server: http://localhost:7071
- 2 Azure Functions: `chat`, `livingAtlasSearch`

## [0.1.0] - 2025-11-04

### Added
- Initial project scaffolding
- Basic React frontend setup
- Azure Functions backend setup
- Project documentation structure

---

[Unreleased]: https://github.com/msftsean/esri-app-finder-demo/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/msftsean/esri-app-finder-demo/releases/tag/v1.0.0
[0.1.0]: https://github.com/msftsean/esri-app-finder-demo/releases/tag/v0.1.0
