# leave-management-system
## React 및 Nest.js를 활용한 연차 관리 프로젝트

# 연차관리 시스템 (Leave Management System)

## 개요

**연차관리 시스템**은 직원들이 연차를 신청하고, 관리자가 이를 승인 및 추적할 수 있도록 돕는 웹 애플리케이션입니다. 이 시스템은 리액트를 기반으로 개발되었으며, 모든 사용자가 자신의 연차를 관리하고 팀원들의 연차를 승인/거절할 수 있습니다.

## 주요 기능

*   **연차 신청**: 사용자는 연차를 신청하고 사유를 입력할 수 있습니다.
*   **연차 승인/거절**: 사용자는 팀원들의 연차 신청을 승인하거나 거절할 수 있습니다.
*   **연차 조회**: 사용자는 자신의 연차 사용 내역과 잔여 연차를 확인할 수 있습니다.
*   **대시보드**: 연차 현황을 요약하여 보여줍니다.

## 설치 및 실행 방법

### 1\. 클론 및 디렉토리 이동

bash

코드 복사

`git clone https://github.com/your-username/leave-management-system.git cd leave-management-system`

### 2\. 패키지 설치

bash

코드 복사

`npm install`

### 3\. 애플리케이션 실행

bash

코드 복사

`npm start`

## 프로젝트 구조

<pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>css</span><div class="flex items-center"><span class="" data-state="closed"><button class="flex gap-1 items-center"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24" class="icon-sm"><path fill="currentColor" fill-rule="evenodd" d="M7 5a3 3 0 0 1 3-3h9a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3h-2v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-9a3 3 0 0 1 3-3h2zm2 2h5a3 3 0 0 1 3 3v5h2a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1zM5 9a1 1 0 0 0-1 1v9a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-9a1 1 0 0 0-1-1z" clip-rule="evenodd"></path></svg>코드 복사</button></span></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-css"><span class="hljs-attribute">src</span>/
│
├── components/
│   ├── LoginPage<span class="hljs-selector-class">.js</span>
│   ├── Dashboard<span class="hljs-selector-class">.js</span>
│   ├── LeaveRequest<span class="hljs-selector-class">.js</span>
│   ├── LeaveStatus<span class="hljs-selector-class">.js</span>
│   └── NavBar<span class="hljs-selector-class">.js</span>
│
├── App<span class="hljs-selector-class">.js</span>
└── index<span class="hljs-selector-class">.js</span>
</code></div></div></pre>

## 사용 기술

*   **React**: 사용자 인터페이스 구축
*   **Material-UI**: 스타일링 및 UI 컴포넌트
*   **React Router**: 라우팅 관리

## 기여 방법

1.  이 리포지토리를 포크하세요.
2.  새로운 브랜치를 만드세요: `git checkout -b feature/your-feature`
3.  변경 사항을 커밋하세요: `git commit -m 'Add some feature'`
4.  브랜치에 푸시하세요: `git push origin feature/your-feature`
5.  풀 리퀘스트를 생성하세요.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

- - -

추가적인 질문이나 요청 사항이 있다면 언제든지 연락 주세요. 프로젝트에 기여해 주셔서 감사합니다!
