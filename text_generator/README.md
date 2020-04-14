## Text Generator based on ANN Network.
ANN 네트워크 기반의 텍스트 생성 모델.

### Developer

Yoonsoo NA

### Contents
- train.py
    - 훈련 및 테스트를 진행하는 코드.
- combined.txt
    - 훈련 및 테스트에 사용되는 텍스트 형식
    - 각 문장은 앞뒤로 S(start token), E(end token)이 있으며, 이러한 문장들이 한 줄로 연결되어 있다.
- total.txt
    - 음성인식용 수집 데이터에서 텍스트만 추출된 데이터. 
    - 본 데이터를  total.txt 식으로 가공하여 train.py에 데이터로 넣어야 한다.

