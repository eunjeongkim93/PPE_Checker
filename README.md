# PPE_Checker
- 이미지 업로드 시, 해당 인물이 안전모, 조끼, 보호안경 등 PPE를 착용했는지 감지하고, 누락된 항목을 사용자에게 알려줍니다.

핵심 기술:

Azure OpenAI (GPT를 통해 감지 결과 설명)

Azure AI Search (선택적으로 PPE 기준 문서 검색용)

Streamlit (UI)

Azure Functions or Web App (배포 고려)

Python + Azure SDK

YOLOv5/YOLOv8 등 사전 학습된 PPE 감지 모델 (로컬 추론 또는 Azure Custom Vision 가능)
