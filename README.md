# Dog Detection Dataset Project

이 프로젝트는 인벤톤 메이커톤 사전실습 과제 중 AI 영상 데이터 수집 및 모델 준비 2에 해당합니다.

## 폴더 구성

- `images/`: 반려견 이미지 총 100장
- `labels/`: YOLO 형식 라벨링 파일
- `weights/`: 학습된 모델 `best.pt`
- `results/`: 학습 후 결과 이미지 `results.png` 포함

## 모델 정보

- 모델: YOLOv11
- 학습 데이터: 반려견 얼굴 이미지 50장
- 전이학습 사용: `yolov7.pt` → 학습 완료

## 결과 이미지
![결과 이미지](results/results.png)

## 담당자
- 김태현, 경상국립대학교 소프트웨어공학과
