## 그냥 개발하다보니 심심해서 만들어보았다

![image](https://user-images.githubusercontent.com/58325946/217986345-48afe512-2136-49f6-8164-c6e997029776.png)

### 파이썬 flask aws rn 멀티태스킹하다 보니 현기증이온다 2023-02-10 11:39


![image](https://user-images.githubusercontent.com/58325946/219572659-a121cf99-32f9-40bc-8bea-bace270d3edd.png)

![image](https://user-images.githubusercontent.com/58325946/219573145-f4e1e48c-93f7-4482-850a-86ed41dc9bc0.png)


### 모든 기능 구현이 끝났다,,, 혼을 갈아넣은 작품 탄생 2023-02-17



# 마스크 얼굴 탐지모델
https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB
from vision.ssd.mb_tiny_RFB_fd import create_Mb_Tiny_RFB_fd, create_Mb_Tiny_RFB_fd_predictor

# 합성 라이브러리
cv2.seamlessclone
https://pysource.com/2019/05/28/face-swapping-explained-in-8-steps-opencv-with-python/

# opencv-python 라이브러리의 seamlessclone 함수를 활용하여 기존 딥페이크 기술을 개조하는데 참고한 영상
https://pysource.com/2019/04/04/face-swapping-opencv-with-python-part-1/
part 1~6


# 눈 객체 탐지 모델
eye_cascade = cv2.CascadeClassifier('haar/haarcascade_eye.xml') 
### 하르분류기 모델이다
https://github.com/rk45825243/Face-eye-detection-using-Haar-Cascade-classifier/blob/master/Face%20and%20eye%20detect%20using%20haar%20cascade.py

roi parameter에 하르 분류기 - 얼굴 탐지 대신에 mask얼굴 탐지모델을 활용하여 얻은 좌표값을 대입하여
마스크가 착용하여도 눈 검출이 가능하도록 기존의 기능을 직접 개조하였다.

### 눈을 탐지하고, 그에 따른 점수 표기방식을 하는데 참조한 논문

https://pyimagesearch.com/2017/04/24/eye-blink-detection-opencv-python-dlib/
http://vision.fe.uni-lj.si/cvww2016/proceedings/papers/05.pdf

![image](https://user-images.githubusercontent.com/58325946/219863900-f412a9eb-6313-41d1-82a0-75cdfc45a8d0.png)

### 우리 프로젝트를 괴롭혔던 RN 비동기 문제,,, 드디어 해결했다 모든 오류를 해결했다!! 2023-02-18 오후 8:46


########################################################################################################################################
########################################################################################################################################
########################################################################################################################################

## 쌍욕봇 자동번역기능 + 라이브 서버 Api 배포 성공! 2023-03-24 오후 5:34
![image](https://user-images.githubusercontent.com/58325946/227467104-49e1bb3c-89b8-4a2b-8b18-c13c7b9b66d7.png)

