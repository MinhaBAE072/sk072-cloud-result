# sk072-cloud-result

# 음성 생성 애플리케이션 사용 가이드

이 문서는 음성 생성(TTS) 애플리케이션의 접속 정보 및 사용 방법을 안내합니다.

## 1. Swagger UI

애플리케이션의 API 문서는 다음 URL을 통해 Swagger UI에서 확인할 수 있습니다.

* **Swagger UI 접속 URL:** 
  * `https://sk072-tts.skala25a.project.skala-ai.com/swagger-ui/index.html`

## 2. 음성 생성 API 테스트 (웹 브라우저)

웹 브라우저 주소창에 다음 URL을 직접 입력하여 음성 생성을 확인할 수 있습니다.

### 한국어 음성 생성 예시

* **텍스트:** "저는 스칼라 3반 배민하입니다."
* **URL:**
  ```
  https://sk072-tts.skala25a.project.skala-ai.com/api/tts/generate?text=저는 스칼라 3반 배민하입니다.&lang=ko
  ```
* **결과:** `speech.mp3` 파일이 자동으로 다운로드됩니다. 예시 파일 내용은 "저는 스칼라 3반 배민하입니다."라는 음성입니다.

### 영어 음성 생성 예시

* **텍스트:** "Hello, I'm Bae Min-ha and I want to get a job in skcc."
* **URL (텍스트 URL 인코딩 적용):**
  ```
  https://sk072-tts.skala25a.project.skala-ai.com/api/tts/generate?text=Hello, I'm Bae Min-ha and I want to get a job in skcc.&lang=en
  ```
* **결과:** `speech.mp3` 파일이 자동으로 다운로드됩니다. 예시 파일 내용은 "Hello, I'm Bae Min-ha and I want to get a job in skcc."라는 음성입니다.
