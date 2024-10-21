# MemoPing(메모핑) Frontend 📒✨

> 메모를 간단히 기록할 수 있는 메모핑! 메모가 어렵다구? 메모핑과 함께 간단하고 쉽게 메모할 수 있어!  
실시간 동기화를 통해 누구나 쉽게 메모를 관리할 수 있는 간단한 웹 애플리케이션입니다.  
프로젝트를 시작한 계기: https://devpearl.tistory.com/15 

## Overview

A simple memo web application built with Next.js. The application allows users to create, read, and delete memos with real-time synchronization using a Test-Driven Development (TDD) approach.


> 메모를 간단히 기록할 수 있는 메모핑! 메모가 어렵다구? 메모핑과 함께 간단하고 쉽게 메모할 수 있어!  
실시간 동기화를 통해 누구나 쉽게 메모를 관리할 수 있는 간단한 웹 애플리케이션입니다.  
프로젝트를 시작한 계기: https://devpearl.tistory.com/15 

## Overview

A simple memo web application built with Next.js and NodeJS express server, Mongo DB. The application allows users to create, read, and delete memos with real-time synchronization using a Test-Driven Development (TDD) approach.

## Features

- ✏️ **Create Memo**: Add new memos with a simple input form.
- ✏️ **Update Memo**: Update memo and save changes.
- 📄 **Read Memo**: View a list of memos, which updates in real-time.
- 🗑️ **Delete Memo**: Remove memos from the list with a single click.
- 🔄 **Real-time Synchronization**: All changes are instantly reflected for all users through Mongo DB.
- ✅ **Test-Driven Development**: TDD methodology applied with Jest and React Testing Library.

## Tech Stack

- **Frontend**: Next.js, TypeScript
- **Backend**: Node.js, Express
- **DataBase**: MongoDB
- **Testing**: Vitest, 
- **Styling**: Tailwind CSS, Next UI

## **MemoPing 프로젝트 개발 타임라인**

### **V0.0.1: 기본 프론트엔드 CRUD 기능 구현**
> **목표**: 메모를 생성, 읽기, 수정, 삭제할 수 있는 기본 UI와 상태 관리 로직 구현, vitest를 이용한 TDD 방식으로 검증.
- **기능 구현**:
  - 메모 생성, 읽기, 수정, 삭제 기능 UI 구현.
  - 각 기능에 대한 단위 테스트 작성 (Vitest).
  - TDD로 개발하며, 테스트를 먼저 작성하고 그에 맞는 기능 코드 작성.
- **완료 목표**: `2024-10-15`
- **개발**: `2024-10-12 ~ 2024-10-15`

---

### **V0.0.3: CSS 스타일링 및 UI 개선**
> **목표**: Tailwind CSS와 Next UI를 사용하여 프로젝트의 기본 스타일링을 적용하고, 사용자 경험을 개선.
- **기능 구현**:
  - 메모 리스트와 메모 작성 폼의 기본 스타일링 적용.
  - 반응형 디자인 설정 (모바일, 태블릿, 데스크톱 지원).
  - 사용자의 편의성을 위한 인터랙션 추가 (hover, active 등).
  - 기본 UI 컴포넌트들을 Next UI로 마이그레이션.
  - 스타일링 관련 UI 테스트 작성.
- **완료 목표**: `2024-`

---

### **V0.0.4: 전체 E2E 테스트**
> **목표**: Playwright 또는 Cypress를 사용해 사용자 흐름과 전체 기능에 대한 E2E 테스트 작성 및 검증.
- **기능 구현**:
  - 사용자 플로우 시나리오 작성 (메모 생성, 수정, 삭제 시나리오).
  - Playwright 또는 Cypress 설정 및 환경 구성.
  - 각 주요 기능에 대한 E2E 테스트 작성 (e.g., 메모를 작성하고 리스트에 표시되는지 검증).
  - CI/CD 파이프라인과 연동하여 E2E 테스트 자동화.
- **완료 목표**: `2024-`

---

### **V0.0.5: 배포 및 성능 최적화**
> **목표**: 프로젝트를 Vercel 또는 AWS에 배포하고, 성능 및 로딩 속도 최적화.
- **기능 구현**:
  - Vercel에 Next.js 프론트엔드 배포 및 Express 서버와 연결.
- **완료 목표**: `2024-`

---

### **V0.0.6: 사용자 피드백 반영 및 기능 개선**
> **목표**: 초기 사용자 피드백을 반영하여 UX/UI 및 기능 개선.
- **기능 구현**:
  - 피드백 기반으로 불편했던 UI 개선.
  - 메모 검색 기능 추가.
  - 실시간 알림 기능 구현 (e.g., 메모가 추가되거나 수정되었을 때).
  - 추가된 기능에 대한 테스트 작성 및 검증.
- **완료 목표**: `2024-`

---

### **V1.0.1: 로그인 및 회원가입 UI 구현**
> **목표**: 사용자 로그인 및 회원가입 페이지 구현, 입력 검증 및 사용자 경험 최적화.
- **기능 구현**:
  - 로그인 및 회원가입 페이지 디자인.
  - 입력 폼 유효성 검사 및 에러 메시지 표시.
  - Vitest를 이용한 테스트.
- **완료 목표**: `2024-`

---

### **V1.0.2: 상태 관리 (Redux) 추가**
> **목표**: 전역 상태를 효율적으로 관리하고, 사용자 인증 상태와 메모 데이터를 저장.
- **기능 구현**:
  - Redux 설치 및 기본 스토어 설정.
  - 사용자 정보 및 메모 리스트 상태 관리.
  - 상태 변화에 따른 UI 업데이트 구현.
  - Vitest를 통한 상태 관련 테스트 작성.
- **완료 목표**: `2024-`

---

### **V1.0.3: WebSocket을 통한 실시간 UI 동기화**
> **목표**: WebSocket을 통해 메모 작성, 수정, 삭제 시 UI 실시간 업데이트 구현.
- **기능 구현**:
  - WebSocket 클라이언트 설정 및 서버와의 연결.
  - 메모 데이터 변경 시 실시간으로 UI 업데이트.
  - 실시간 업데이트에 따른 상태 관리 및 동기화 처리.
  - WebSocket 관련 테스트 작성 (Vitest).
- **완료 목표**: `2024-`

---

### **V1.0.4: GraphQL 클라이언트 적용**
> **목표**: GraphQL을 사용한 데이터 요청 최적화, 더 유연한 데이터 쿼리 처리.
- **기능 구현**:
  - Apollo Client 설정 및 GraphQL 쿼리 작성.
  - 메모 CRUD 작업에 GraphQL 적용.
  - GraphQL 관련 컴포넌트 및 데이터 요청 테스트 작성 (Vitest).
- **완료 목표**: `2024-`



## **타임라인 요약**

| 단계       | 목표                                  | 완료 목표      |
|------------|-------------------------------------|----------------|
| **V0.0.1** | 기본 프론트엔드 CRUD 구현 (TDD)       | `2024-10-15`   |
| **번외**   | 서버 구축을 위한 Node.js, mongoDB 공부| `2024-10-22`   |
| **V0.0.2** | (백엔드) express 서버                | `2024-`   |
| **V0.0.3** | CSS 스타일링 및 UI 개선                | `2024-`   |
| **V0.0.4** | 전체 E2E 테스트                       | `2024-`   |
| **V0.0.5** | 배포 및 성능 최적화                   | `2024-`   |
| **V0.0.6** | 사용자 피드백 반영 및 기능 개선       | `2024-`   |
| **V1.0.1** | 로그인 및 회원가입 기능 추가 및 세션 관리   | `2024-`   |
| **V1.0.2** | 상태 관리 추가                      | `2024-`   |
| **V1.0.3** | Change Stream 및 WebSocket 실시간 동기화 | `2024-`   |
| **V1.0.4** | GraphQL로 적용  | `2024-`   |


### **메모핑 V0.0.1** 
> **목표: 메모를 생성, 읽기, 수정, 삭제할 수 있는 로직 구현, vitest를 이용한 TDD 방식으로 검증.**

### **V0.0.1 CRUD 기능 세부 분할 및 체크리스트**

#### **1. 메모 생성 (Create)**

- ✅ **입력 상태 관리**: 사용자의 입력에 따라 상태가 업데이트.
  - ✅ 입력 필드에 텍스트를 입력할 때 상태가 올바르게 변경되는지 확인.
- ✅ **입력 유효성 검사**: 빈 값일 경우 메모는 추가되지 않고 alert 창 띄움.
  - ✅ 빈 값 입력 시 alert 뜨는지 확인.
  - ✅ 빈 값 입력 시 메모가 추가되지 않는지 확인.

#### **2. 메모 읽기 (Read)**
- ✅ **메모 목록 렌더링**: 가져온 메모 목록을 화면에 표시.
  - ✅ 메모의 제목과 메시지 표시
  - ✅ 메모가 없는 경우, "메모가 없습니다" 메시지 표시.

#### **3. 메모 수정 (Update)**

- ✅ **수정 버튼 추가**: 각 메모 아이템에 수정 버튼 추가.
- ✅ **수정 상태 전환**: 수정 버튼 클릭 시, 수정 가능한 입력 필드로 전환.
  - ✅ 수정 버튼 클릭 시, 기존 메모 내용이 입력 필드에 표시.
- ✅ **수정 내용 저장**: 수정된 내용이 저장됨.
- [ ] **수정 취소**: 수정 상태에서 취소 버튼을 클릭 시, 이전 내용 유지.

#### **4. 메모 삭제 (Delete)**

- ✅ **삭제 버튼 추가**: 각 메모 아이템에 삭제 버튼 추가.
- [ ] **삭제 확인 모달**: 삭제 버튼 클릭 시, 확인 모달 표시.
- ✅ **메모 삭제**: 메모 삭제.
- [ ] **삭제 중 로딩 상태 표시**: 삭제 중 로딩 상태를 표시.


