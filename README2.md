## Mask_RCNN 중 수정한 곳
+ mrcnn 폴더 내 visualize.py 수정
+ samples 폴더 내 clothes 폴더 생성 후 clothes 폴더 내에 데이터 셋 폴더와 clothes.py를 추가
+ 데이터 셋은 너무 커서 깃허브에 업로드 불가 (코드 사용시 로컬에서 데이터셋을 준비한 후 사용)

## Mask_RCNN 사용법 (Colab 기준)
1. Mask_RCNN git clone 하기
2. setup.py 파일 설치
3. cocoapi 설치
4. google drive 마운트하기
5. 모델 학습 - !python 'clothes.py가 있는 경로' train --weights=coco
6. 모델 테스트 - !python 'clothes.py가 있는 경로' splash --weights=저장된 학습 모델 가중치 파일이름

###### clothes.py에 있는 데이터 셋 경로를 수정해서 Mask_RCNN 이용 (상,하의 / 셔츠 카라 유형)
