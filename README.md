<div align="center">
 
# Korean Clinical Diagnosis Simulation System
MDPI Bioengineering: [Conformer-Based Dental AI Patient Clinical Diagnosis Simulation Using Korean Synthetic Data Generator for Multiple Standardized Patient Scenarios](https://www.mdpi.com/2306-5354/10/5/615)
</div>

---

## 임상진단 실습을 위한 NLP 시스템

* 임상실습 교육의 목표는 임상 환경에서 이론적 지식을 실제로 적용하는 능력을 함양하고, 전문 의료인으로서의 성장을 촉진하는 데 있습니다. 이를 효과적으로 달성하는 방법 중 하나는 표준화 환자(Standardized Patient, SP)를 활용하여 학생들이 실제 환자 인터뷰에 익숙해지도록 하고, 교육자가 임상 수행 기술을 평가할 수 있도록 하는 것입니다. 그러나 표준화 환자를 활용하는 교육은 배우 고용에 따른 비용과 이들을 교육할 전문 교육자의 부족이라는 과제에 직면하고 있습니다.

* 본 연구에서는 이러한 문제를 해결하기 위해 딥러닝을 활용하여 배우를 대체하는 방안을 제안합니다. 이를 위해 Conformer 모델을 활용하여 AI 환자를 구현하고, 진단 질문에 대한 응답 데이터를 수집하기 위해 한국어 표준화 환자 시나리오 데이터 생성기를 개발하였습니다. 이 생성기는 미리 준비된 질문과 답변을 기반으로, 제공된 환자 정보를 토대로 시나리오를 자동으로 생성하도록 설계되었습니다.

<img src = https://github.com/kkkkkkkm/denti_chat/blob/main/img/den.png width = "100%" height = "100%">




## File
* chatbot_lib.ipynb:
  * 모델 구조와 학습된 파라미터를 불러오는 추론용

* chatbot_model.ipynb:
  * Transformer 기반 모델 학습

* chatbot_model_Conformer_submit.ipynb:
  * Conformer 기반 모델 학습 

* co_chatbot.ipynb:
  * 추론 모델 load 후 질의응답 

* preprocessing_soy_embedding.ipynb:
  * 단어 임베딩 및 맞춤법 모델 학습
