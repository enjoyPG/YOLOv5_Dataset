# YOLOv5_Dataset

## 각 Dataset 폴더 안에 모든 자료 있음

## BORDER색을 변경하고 싶다면
[일반 이미지는 아래 방법으로 하면 됨]
yolov5/utils/plots.py에서 아래 코드를 수정해주면 된다.
 hex = ('FF3838', 'FF9D97', 'FF701F', 'FFB21D', 'CFD231', '48F90A', '92CC17', '3DDB86', '1A9334', '00D4BB', 
        '2C99A8', '00C2FF', '344593', '6473FF', '0018EC', '8438FF', '520085', 'CB38FF', 'FF95C8', 'FF37C7') 

[영상으로 뽑아낼 때는 라이브러리에서 색을 가져오기 때문에 라이브러리에 접근해야함 코랩기준]
/usr/local/lib/python3.10/dist-packages/ultralytics/utils/plotting.py에서
hex = ('FF3838', 'FF9D97', 'FF701F', 'FFB21D', 'CFD231', '48F90A', '92CC17', '3DDB86', '1A9334', '00D4BB', 
        '2C99A8', '00C2FF', '344593', '6473FF', '0018EC', '8438FF', '520085', 'CB38FF', 'FF95C8', 'FF37C7') 
수정하면된다. (진짜 구글링 아무리해도 안나오고.. 2틀만에 소스코드 뜯어서 해결함..) 빡시다

아래로 수정함
hexs = ('65FF74', 'F081F7', 'F22C2C', '2C33F2', 'CFD231', '48F90A', '92CC17', '3DDB86', '1A9334', '00D4BB',
        '2C99A8', '00C2FF', '344593', '6473FF', '0018EC', '8438FF', '520085', 'CB38FF', 'FF95C8', 'FF37C7')
## 참고 자료
https://m.blog.naver.com/ehdrndd/222462355643
