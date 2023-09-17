# YOLOv5_Dataset

## 각 Dataset 폴더 안에 모든 자료 있음

## YOLOv5_nidaleeDataset 설명(아래 3개의 파일이 함께 들어있음)
 1. colab notebook
 2. best.pt는 학습시켜놓은 weight파일로 /content/yolov5/runs/train/YOLOv5_nidalee/weights/best.pt 경로에 위치해야함(yolov5를 깃에서 받아서 설치하고 해당경로에 넣어두면 제가 학습해둔 weight파일을 바로 쓸 수 있음)
 3. 2.mp4는 원본, 2_yolo.mp4는 detection 적용해둔 영상


## 추가로 BORDER색을 변경하고 싶다면
yolov5/utils/plots.py에서 아래 코드를 수정해주면 된다.

 hex = ('FF3838', 'FF9D97', 'FF701F', 'FFB21D', 'CFD231', '48F90A', '92CC17', '3DDB86', '1A9334', '00D4BB', 
        '2C99A8', '00C2FF', '344593', '6473FF', '0018EC', '8438FF', '520085', 'CB38FF', 'FF95C8', 'FF37C7') 


## 참고 자료
https://m.blog.naver.com/ehdrndd/222462355643
