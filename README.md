## 🧑🏻‍💻 ZERIONG

<br>

안녕하세요, UX/DX지향 개발자 ZERIONG 입니다.

불편함이 친숙함으로 전환되는 순간을 즐기며

개발을 이어가고 있습니다.

<br>

## 🛠️ Stacks
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Nest.js](https://img.shields.io/badge/Nest.js-E0234E?style=flat&logo=nestjs&logoColor=white)
![Orval](https://img.shields.io/badge/Orval-536AFE?style=flat&logo=openapi-initiative&logoColor=white)

<br>

## 🤝 Open Source Contribution

<details>
  <summary id="datail">
    <h3>🐠 Orval</h3>
  </summary>
  
  - orval-labs/orval [#3172](https://github.com/orval-labs/orval/pull/3172) **`⭐ Milestone`** React 샘플 앱을 CRA에서 Vite로 마이그레이션
  - orval-labs/orval [#3169](https://github.com/orval-labs/orval/pull/3169) **`⭐ Milestone`** watch 모드 시작 시 불필요한 다중 재생성 방지
  - orval-labs/orval [#3199](https://github.com/orval-labs/orval/pull/3199) **`⭐ Milestone`** fetch 클라이언트 내 긴 삼항 표현식을 다중 라인으로 리팩터링
  - orval-labs/orval [#3180](https://github.com/orval-labs/orval/pull/3180) **`⭐ Milestone`** fetch 클라이언트에 커스텀 fetch 함수 주입을 위한 `fetcher` 옵션 추가 및 docs 수정
  - orval-labs/orval [#3221](https://github.com/orval-labs/orval/pull/3221) **`⭐ Milestone`** OpenAPI 3.0 boolean exclusiveMinimum/Maximum mock 생성 오류 수정
  - orval-labs/orval [#3229](https://github.com/orval-labs/orval/pull/3229) **`⭐ Milestone`** propertyNames.const 지원으로 typed Record 키 타입 생성 정확도 개선
  - orval-labs/orval [#3230](https://github.com/orval-labs/orval/pull/3230) **`⭐ Milestone`** OpenAPI 3.1 nullable object 배열에서 mock properties 누락 수정
  - orval-labs/orval [#3261](https://github.com/orval-labs/orval/pull/3261) **`⭐ Milestone`** fetch 응답 파싱 전략에 error content type 포함 (#3222 후속)
  - orval-labs/orval [#3338](https://github.com/orval-labs/orval/issues/3338) **`💡 Proposal`** 불필요한 React default import 이슈 발견 → skipErrorChecking 스코핑 수정
  - orval-labs/orval [#3168](https://github.com/orval-labs/orval/pull/3168) ✅ Angular filterParams에서 null 리터럴 사용하여 TypeScript 오류 수정
  - orval-labs/orval [#3182](https://github.com/orval-labs/orval/pull/3182) ✅ content type 기반 isBlob 감지로 Angular Query blob 응답 누락 수정
  - orval-labs/orval [#3191](https://github.com/orval-labs/orval/pull/3191) ✅ 라우트 배열에서 path param 뒤에 dash가 올 때 발생하는 구문 오류 수정
  - orval-labs/orval [#3196](https://github.com/orval-labs/orval/pull/3196) ✅ Angular 다중 content-type HTTP 요청에서 query params 누락 수정
  - orval-labs/orval [#3198](https://github.com/orval-labs/orval/pull/3198) ✅ path params 및 tags-split 환경에서 mutationInvalidates 코드 생성 오류 수정
  - orval-labs/orval [#3207](https://github.com/orval-labs/orval/pull/3207) ✅ CLI에 `--fail-on-warnings` 플래그 추가하여 경고 시 종료 지원
  - orval-labs/orval [#3206](https://github.com/orval-labs/orval/pull/3206) ✅ components만 있는 OpenAPI 스펙에서 Zod 스키마 생성 지원
  - orval-labs/orval [#3205](https://github.com/orval-labs/orval/pull/3205) ✅ MSW mock handler에서 void union 타입 처리 수정
  - orval-labs/orval [#3204](https://github.com/orval-labs/orval/pull/3204) ✅ schemas barrel import 경로에 fileExtension 누락 수정
  - orval-labs/orval [#3220](https://github.com/orval-labs/orval/pull/3220) ✅ Hono 생성 handler 파일에 orval 표준 파일 헤더 누락 수정
  - orval-labs/orval [#3237](https://github.com/orval-labs/orval/pull/3237) ✅ mutationInvalidates params에 `{ literal: string }` 문법 추가로 문자열 리터럴 지원
  - orval-labs/orval [#3222](https://github.com/orval-labs/orval/pull/3222) ✅ fetch 응답 body를 content-type 기반으로 파싱하도록 수정 (JSON.parse 고정 제거)
  - orval-labs/orval [#3238](https://github.com/orval-labs/orval/pull/3238) ✅ angular-query 클라이언트에 usePrefetch 지원 추가
  - orval-labs/orval [#3247](https://github.com/orval-labs/orval/pull/3247) ✅ Zod date-time 포맷에 `{ offset: true }` 기본값 적용으로 RFC3339 호환 수정
  - orval-labs/orval [#3248](https://github.com/orval-labs/orval/pull/3248) ✅ binary 스키마의 contentMediaType 업그레이드 시 ArrayBuffer mock 생성 수정
  - orval-labs/orval [#3249](https://github.com/orval-labs/orval/pull/3249) ✅ Angular httpResource 출력을 tags/tags-split 모드에서 tag별 스코핑 수정
  - orval-labs/orval [#3239](https://github.com/orval-labs/orval/pull/3239) ✅ OpenAPI validation 실패를 error 대신 warning으로 처리 (fastapi.sse 등 지원)
  - orval-labs/orval [#3267](https://github.com/orval-labs/orval/pull/3267) ✅ 안전한 samples에 `clean: true` 활성화 및 레이아웃 규칙 문서화
  - orval-labs/orval [#3292](https://github.com/orval-labs/orval/pull/3292) ✅ Hono handler preamble 갱신 및 hono.handlers 옵션의 import 경로 수정
  - orval-labs/orval [#3293](https://github.com/orval-labs/orval/pull/3293) ✅ Zod에서 multipart/urlencoded 요청의 Body 스키마 생성 수정
  - orval-labs/orval [#3290](https://github.com/orval-labs/orval/pull/3290) ✅ 생성된 invalidate 함수에 queryOptions mutator 적용 (useInvalidate 누락 수정)
  - orval-labs/orval [#3303](https://github.com/orval-labs/orval/pull/3303) ✅ JSDoc을 URL helper 대신 메인 함수에 부착하도록 수정
  - orval-labs/orval [#3304](https://github.com/orval-labs/orval/pull/3304) ✅ enumGenerationType: 'enum' 사용 시 빈 import type 구문 생성 방지
  - orval-labs/orval [#3306](https://github.com/orval-labs/orval/pull/3306) ✅ Angular 클라이언트에서 binary 응답 타입 컴파일 오류 수정
  - orval-labs/orval [#3307](https://github.com/orval-labs/orval/pull/3307) ✅ x-enumDescriptions/x-enumNames에 Map 포맷 지원 추가
  - orval-labs/orval [#3309](https://github.com/orval-labs/orval/pull/3309) ✅ additionalProperties 내 $ref 타입의 누락된 import 추가 (split schema)
  - orval-labs/orval [#3325](https://github.com/orval-labs/orval/pull/3325) ✅ 자동 생성된 `enabled` 옵션에 null-check 적용 (0 값 비활성화 방지)
  - orval-labs/orval [#3336](https://github.com/orval-labs/orval/pull/3336) ✅ 재귀적 external $ref 인라이닝 시 순환 참조 해소
  - orval-labs/orval [#3339](https://github.com/orval-labs/orval/pull/3339) ✅ Zod object defaults에서 `as const`로 리터럴 타입 보존
  - orval-labs/orval [#3345](https://github.com/orval-labs/orval/pull/3345) ✅ TypeDoc skipErrorChecking을 생성된 entry point로 스코핑하여 TS6133 오류 수정
</details>

<details>
  <summary id="datail">
    <h3>📚 VSCode Extensions</h3>
  </summary>
  
  - vscode-folder-colorizer [#20](https://github.com/egorovsa/vscode-folder-colorizer/issues/20) **`💡 Proposal`** pathColors를 User-level 설정에 저장하는 옵션 제안 → 메이저 버전 반영
</details>
