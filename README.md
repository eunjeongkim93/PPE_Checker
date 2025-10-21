# PPE_Checker

1. 프로젝트 개요
   
   - 프로젝트명: PPE(산업현장 인체 보호장비) 체크 시스템
   
   - 문제
   
     🚫 안전점검을 위해 현장에서 이미지 업로드 시, 해당 직원이 보호장비(안전모, 조끼 등)를 제대로 착용했는지 확인이 필요
     
   - 누구를 위한 건가요?

     👷🏻‍♀️ 안점점검하려는 직원
     
   - 해결 방법

     🔑 이미지를 업로드하면 해당 직원이 보호장비를 제대로 착용했는지 확인 후, 누락 항목을 사용자에게 알려줌으로서 위험방지

2. 프로젝트 구조
   
mvp_ppe_checker/

   ├── app.py                      # Streamlit 앱 진입점
   
   ├── ppe_detector.py            # 이미지 분석 (YOLO 모델 사용)
   
   ├── azure_gpt.py               # OpenAI GPT API 연동
   
   ├── utils.py                   # 유틸 함수 (이미지 처리 등)
   
   ├── requirements.txt
   
   ├── .streamlit/
   
   │   └── config.toml
   
   └── assets/
   
       └── sample.jpg             # 샘플 이미지
