# 20-1-BAS
## 20-1 생체인증보안(Biometric Authentication Security)
### 지문 인식 시스템 (Fingerprint recognition system)
- 사용한 데이터 : 144 X 144크기, bmp형식, Grayscale 지문 이미지       
```
ID 8명 X 10개 샘플 = 총 80개         
학습 데이터 : ID 8명 X 8개 샘플 = 64개
테스트 데이터 : ID 8명 X 2개 샘플 = 16개
```
- 전처리 : 이진화, 세선화, 열림과 닫힘 진행        
- 성능 평가 : identification, verification(FRR, FAR)           

### 얼굴 인식 시스템 (Face recongnition system)
- 사용한 데이터 : 56 X 46크기, bmp형식, Grayscale 얼굴 이미지   
```
ID 270명 X 5개 샘플 = 총 1350개         
학습 데이터 : ID 160명 X 5개 샘플 = 800개
테스트 데이터 : ID 110명 X 5개 샘플 = 550개
쿼리 데이터 : ID 별 1개 = 110개
```
- PCA(Principal Component Analysis) 기반 분석       
- 성능 평가 : identification, verification(FRR, FAR)   

### 홍채 인식 시스템 (Iris recognition system)
- 사용한 데이터 : 32 X 266크기, bmp형식, Grayscale Iris Code  
```
ID 189명 X 10개 샘플 = 총 1890개         
학습 데이터 : ID 120명 X 10개 샘플 = 1200개
테스트 데이터 : ID 69명 X 10개 샘플 = 690개
쿼리 데이터 : ID 별 2개 = 138개
```
- PCA(Principal Component Analysis) 기반 분석       
- 성능 평가 : identification, verification(FRR, FAR)   
