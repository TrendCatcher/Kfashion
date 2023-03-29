# Kfashion

## 🔍 실행환경

(a)로컬 CPU (b) Colab 


## 📮 협업: 형상관리, 통합
- 팀장의 repository를 각자 fork하여 진행함.
  - clone하여 각자의 로컬에서 기능개발
  - git checkout으로 자신의 브랜치를 생성
  - 각자의 로컬에서 개발 진행
  - 기능 구현후 addd, commit하여 최종적으로 main 브랜치에 **PullRequest
  - 팀장이 검수 후 병합(merge)


## 🚨 T기능구현

### training 로그 생성
- 로컬 CPU 환경에서 학습
- testjacket 폴더에서 train.py로 학습시켜주세요.

### Colab 환경에서 학습
1. Kfashion 실습데이터를 자신의 구글드라이브에 업로드
2. 모든 클래스가 섞인 하나의 데이터셋으로 통합한 학습 > Colab_mmdetection_kfashion_v1.ipynb를  순서대로 실행
3. 클래스별로 여러개의 테이터셋으로 여러번 학습 > Colab_mmdetection_kfashion_v2.ipynb를 순서대로 실행
