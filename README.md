# Candy-Detection using Yolo11s, Yolo26s, Yolo26n


<img width="608" height="1033" alt="Screenshot 2026-04-24 103747" src="https://github.com/user-attachments/assets/96147673-dcc1-4c7f-809e-bfb86da2377d" />


<img width="607" height="1079" alt="Screenshot 2026-04-24 103704" src="https://github.com/user-attachments/assets/27bdb70c-310d-4dcf-97e6-ff55c16b095d" />


<img width="597" height="1079" alt="Screenshot 2026-04-24 103721" src="https://github.com/user-attachments/assets/1bc4f475-4c61-4452-9322-4d49c6fb0c3f" />



In here we have made a model which will detect candy and gives the name of that candy

## if you are running in Colab (use yolo_detect_for_colab.py)
Run this to detect:
```
!python yolo_detect_for_colab.py \
  --model /content/my_model_yolo26s.pt \
  --resolution 478x850 \
  --source /content/input.mp4 \
  --output /content/output.mp4
```
## if you are running in local (use yolo_detect.py)
Run this to detect:
```
!python yolo_detect.py \
  --model /content/my_model_yolo26s.pt \
  --resolution 478x850 \
  --source /content/input.mp4 \
  --output /content/output.mp4
```

* In here i have used my_model_yolo26s.pt(yolo26s) you can use different models
* resolution should be same as your input video resolution
* give the input video path as your source
* Then output path as your output

## if you want to detect through webcam
```
!python yolo_detect.py \
  --model /content/my_model_yolo26s.pt \
  --resolution 478x850 \
  --source usb0
```

