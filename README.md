🏗️ HeavyGuard AI - 건설 현장 스마트 안전 관제 시스템

HeavyGuard AI는 스마트폰 카메라와 인공지능(AI)을 활용하여 건설 현장의 위험 요소를 실시간으로 감지하고 분석하는 모바일 웹 기반 안전 보조 도구입니다. 별도의 앱 설치 없이 링크 접속만으로 현장에서 즉시 활용할 수 있습니다.

(실제 앱 스크린샷으로 교체해주세요)

🚀 주요 기능

1. ⚡ 실시간 위험 모니터링 (Real-time Monitoring)

협착/충돌 방지: 스마트폰 내장 AI(TensorFlow.js)가 0.1초 단위로 **근로자(Person)**와 **건설 장비(Vehicle)**를 감지합니다.

즉각 경고: 작업자와 장비가 한 화면에 동시에 포착되면 즉시 🔴 위험 경고(협착 위험) 알림을 띄웁니다.

데이터 비용 Zero: 영상 데이터를 서버로 전송하지 않고 사용자 휴대폰에서 직접 처리(On-device)하므로 데이터 소모가 적고 보안에 안전합니다.

2. 🧠 AI 정밀 진단 (AI Diagnosis)

Google Gemini Pro Vision 연동: 현장 상황을 촬영하여 거대 언어 모델(LLM)이 정밀 분석합니다.

종합 안전 점검:

🏗 장비: 전도 위험, 아웃트리거 설치, 지반 상태 확인

🚧 시설: 개구부 덮개, 안전난간 미설치, 추락 위험 구간

👷 근로자: 안전고리 체결 여부, 안전모/보호구 착용 상태

⚡ 환경: 전선 노출, 인화물질 방치, 정리정돈 불량

보고서 생성: 분석된 결과를 공식 안전 점검 리포트 형식으로 변환하여 보여줍니다.

3. 📄 PDF 리포트 저장 및 인쇄

AI가 작성한 진단 결과를 즉시 PDF 파일로 저장하거나 현장 사무실 프린터로 인쇄할 수 있습니다.

진단 일시, 현장 사진, 위험 요인, 긴급 조치 사항이 포함된 문서를 자동으로 생성합니다.

4. 📱 모바일 최적화 (iOS/Android)

App-like Experience: 앱 설치 없이 웹브라우저(Safari, Chrome)에서 네이티브 앱처럼 부드럽게 작동합니다.

직관적인 UI: 장갑을 낀 상태에서도 조작하기 쉬운 심플한 버튼과 다이내믹 아일랜드 스타일의 알림창을 제공합니다.

카메라 제어: 줌(Zoom), 플래시(Flash), 전/후면 카메라 전환 기능을 지원합니다.

🛠️ 기술 스택 (Tech Stack)

Frontend: HTML5, React 18, Tailwind CSS

AI Engine (Real-time): TensorFlow.js (COCO-SSD MobileNet v2)

AI Engine (Diagnosis): Google Gemini API (gemini-1.5-flash)

Deployment: GitHub Pages (Static Hosting)

🏁 사용 방법 (Getting Started)

1. 사전 준비

이 앱의 '정밀 진단' 기능을 사용하기 위해서는 Google Gemini API 키가 필요합니다.

Google AI Studio에 접속하여 무료 API 키를 발급받으세요.

앱 실행 후 우측 상단 설정(⚙️) 버튼을 눌러 키를 입력하세요. (키는 브라우저에만 안전하게 저장됩니다.)

2. 실행

배포된 URL(예: https://your-id.github.io/HeavyGuard-AI)에 접속합니다.

카메라 권한을 허용합니다.

[실시간 모니터링] 모드로 현장을 비추며 충돌 위험을 감지합니다.

구체적인 위험이 의심되면 셔터 버튼을 눌러 **[정밀 진단]**을 수행합니다.

⚠️ 면책 조항 (Disclaimer)

본 애플리케이션은 현장 안전 관리를 보조하기 위한 **도구(Tool)**입니다.

AI의 분석 결과는 100% 정확하지 않을 수 있으며, 법적 효력이 없습니다.

최종적인 안전 판단과 책임은 현장 관리자 및 안전 책임자에게 있습니다.

반드시 KOSHA(안전보건공단)의 공식 안전 가이드를 준수해 주십시오.

📄 License

This project is licensed under the MIT License.