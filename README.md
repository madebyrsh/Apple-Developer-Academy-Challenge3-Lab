# 🧪 Apple-Developer-Academy-Challenge3-Lab

![Platform](https://img.shields.io/badge/platform-visionOS-blue)
![Language](https://img.shields.io/badge/language-Swift-orange)
![Framework](https://img.shields.io/badge/framework-SwiftUI-green)
![Framework](https://img.shields.io/badge/framework-RealityKit-purple)
![Framework](https://img.shields.io/badge/framework-ARKit-black)

---

<a id="purpose"></a>

# 🎯 저장소 목적

> Challenge3 팀 프로젝트에서 사용된 기능을 직접 재구현하며 학습하기 위한 개인 저장소

Apple Developer Academy @ POSTECH Challenge3 과정에서 개발 중인 팀 프로젝트의 기능들을 직접 다시 구현하며 학습하기 위한 저장소입니다.

이 저장소의 목적은 단순히 코드를 읽는 것이 아니라,

- 기능 분석
- 핵심 개념 이해
- 기능 재구현
- 구현 검증

과정을 통해 기능을 완전히 자신의 것으로 만드는 것입니다.

---

# 🗂 목차

- [저장소 목적](#purpose)
- [소개](#introduction)
- [기술 스택](#tech-stack)
- [학습 목표](#learning-goals)
- [학습 워크플로우](#workflow)
- [폴더 구조](#folder-structure)
- [브랜치 전략](#branch-strategy)
- [커밋 컨벤션](#commit-convention)
- [테스트 환경](#testing-environment)
- [작성자](#author)
- [License](#license)

---

<a id="introduction"></a>

# 📱 소개

Challenge3-Lab은 Challenge3 팀 프로젝트에서 사용된 기능들을 독립적으로 다시 구현하며 학습하기 위한 공간입니다.

이 저장소에서는 다음과 같은 기능을 재구현하며 이해도를 높이는 것을 목표로 합니다.

- Spatial Interaction
- Plane Detection
- World Anchor
- Persistence
- Window Management
- RealityKit Interaction
- Spatial UI/UX

---

<a id="tech-stack"></a>

# 🛠 기술 스택

## Language & Frameworks

- Swift
- SwiftUI
- RealityKit
- ARKit
- SwiftData

---

## Architecture

- MVVM

---

## Tools

- Xcode
- Reality Composer Pro
- GitHub
- Notion
- Figma

---

<a id="learning-goals"></a>

# 🌟 학습 목표

## Team Project Reconstruction

- 팀 프로젝트 기능 분석
- 핵심 개념 이해
- 기능 재구현
- 구현 검증

---

## visionOS Understanding

- Spatial Computing 이해
- RealityKit 이해
- ARKit 이해
- World Anchor 이해
- Persistence 이해

---

## Independent Development

- 기능을 직접 설계할 수 있는 수준 도달
- 기능을 처음부터 구현할 수 있는 수준 도달

---

<a id="workflow"></a>

# 🔄 학습 워크플로우

```text
1. Team Project 기능 분석

↓

2. 핵심 개념 이해

↓

3. 브랜치 생성

↓

4. 기능 재구현

↓

5. 구현 검증

↓

6. Main 브랜치 병합
```

---

<a id="folder-structure"></a>

# 🧱 폴더 구조

```text
📦 Apple-Developer-Academy-Challenge3-Lab
┣ 📂 Experiments
┃ ┗ 📂 SpatialBox
┃
┣ 📂 Assets
┃
┣ 📜 README.md
┗ 📜 .gitignore
```

---

<a id="branch-strategy"></a>

# 🔖 브랜치 전략

```text
main
```

- 안정적인 학습 기록 브랜치

```text
feat/*
```

- 기능별 재구현 브랜치

예시

```text
feat/box-spawn
feat/box-move
feat/box-hover

feat/plane-detection
feat/world-anchor
feat/persistence

feat/window-management
feat/swiftdata
```

---

<a id="commit-convention"></a>

# 🌀 커밋 컨벤션

```text
English Message [한국어]
```

예시

```text
Initialize SpatialBox experiment [SpatialBox 실험 프로젝트 생성]

Implement box spawning [박스 생성 구현]

Implement world anchor placement [월드 앵커 배치 구현]

Document SpatialBox README [SpatialBox README 작성]
```

---

<a id="testing-environment"></a>

# ✅ 테스트 환경

## Hardware

- Apple Vision Pro M5

---

## Development Environment

- Xcode
- visionOS Simulator
- Latest visionOS SDK

---

<a id="author"></a>

# 🧑‍💻 작성자

**Shayne Ryu**  
UX/UI Designer & iOS Developer  
Apple Developer Academy @ POSTECH (Cohort 2026)

---

<a id="license"></a>

# 📝 License

This repository is intended for personal learning and educational purposes.

---

---

<a id="overview-eng"></a>

# 🇺🇸 English

## Repository Purpose

Challenge3-Lab is a personal repository for rebuilding and understanding features used in the Challenge3 team project.

The goal is not simply to read code, but to fully understand a feature by rebuilding it from scratch.

---

## Learning Goals

- Analyze team project features
- Understand core concepts
- Rebuild features independently
- Validate implementations
- Improve visionOS development skills

---

## Learning Workflow

```text
Analyze Team Project Features

↓

Understand Core Concepts

↓

Create Feature Branch

↓

Rebuild From Scratch

↓

Validate Implementation

↓

Merge Into Main
```

---

## Folder Structure

```text
Apple-Developer-Academy-Challenge3-Lab
├── Experiments
│   └── SpatialBox
│
├── Assets
│
├── README.md
└── .gitignore
```

---

## Branch Strategy

```text
main
feat/*
```

---

## Commit Convention

```text
English Message [한국어]
```

Example:

```text
Implement box spawning [박스 생성 구현]

Implement world anchor placement [월드 앵커 배치 구현]
`
