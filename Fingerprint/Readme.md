### 지문 인식 시스템 (Fingerprint recognition system)
- 사용한 데이터 : 144 X 144크기, bmp형식, Grayscale 지문 이미지       
```
ID 8명 X 10개 샘플 = 총 80개         
학습 데이터 : ID 8명 X 8개 샘플 = 64개
테스트 데이터 : ID 8명 X 2개 샘플 = 16개
```
- 전처리 : 이진화, 세선화, 열림과 닫힘 진행        
- 성능 평가 : identification, verification(FRR, FAR)  
