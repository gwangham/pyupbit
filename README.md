# Bitcoin Trading Bot

비트코인 자동매매 봇 프로젝트입니다. OpenAI의 GPT-4를 활용하여 시장 데이터를 분석하고 매매 결정을 내립니다.

## 주요 기능

- 실시간 시장 데이터 분석
- 기술적 지표 계산 (볼린저 밴드, RSI, MACD 등)
- 공포 탐욕 지수 모니터링
- 뉴스 데이터 분석
- YouTube 트레이딩 전략 분석
- 자동 매매 실행
- 거래 내역 데이터베이스 저장

## 설치 방법

1. 저장소 클론
```bash
git clone https://github.com/gwangham/pyupbit.git
cd pyupbit
```

2. 가상환경 생성 및 활성화
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
```

3. 필요한 패키지 설치
```bash
pip install -r requirements.txt
```

4. 환경 변수 설정
`.env` 파일을 생성하고 다음 정보를 입력하세요:
```
UPBIT_ACCESS_KEY=your_access_key
UPBIT_SECRET_KEY=your_secret_key
OPENAI_API_KEY=your_openai_api_key
SERPAPI_API_KEY=your_serpapi_key
```

## 사용 방법

1. 자동매매 실행
```bash
python autotrade.py
```

2. 대시보드 실행
```bash
streamlit run streamlit_app.py
```

## 주의사항

- 실제 거래에 사용하기 전에 충분한 테스트를 진행하세요.
- API 키는 절대 공개되지 않도록 주의하세요.
- 거래에 따른 손실은 본인의 책임입니다.

## 라이선스

MIT License
