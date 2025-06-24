# 📘 AI 학습 정리

## 1. About GitHub, Markdown, Colab
- [GitHub 사용법](#github-사용법)
- [Markdown 문법](#markdown-문법-정리)  
- [Colab 기초](#colab-기초)

## GitHub 사용법

### ✅ GitHub 계정 만드는 순서 (2025년 기준)

1. **웹 브라우저 열기**
   크롬(Chrome), 엣지(Edge), 사파리(Safari) 중 편한 걸 사용하세요.

2. **GitHub 웹사이트 접속**
   주소창에 아래 주소를 입력하고 Enter 누르세요: https://github.com

3. **회원가입 시작하기**
   화면 오른쪽 위 또는 중간에 있는 Sign up 버튼 클릭

4. **이메일 주소 입력**
   평소 자주 사용하는 이메일을 입력

5. **비밀번호 만들기**
   영어 대문자, 소문자, 숫자, 특수문자를 섞어 안전하게!
   예시: Git1234!hub

6. **사용자 이름(Username) 정하기**
   나만의 고유한 이름을 지어요 (다른 사람이 쓰고 있으면 불가)
   - 예시: jetsunmom, sungsookjang66 등
   - 영어, 숫자, 하이픈(-) 가능 (띄어쓰기 ❌)

### ✅ Repository 만들기 순서

1. **GitHub에 로그인 후 New Repository 클릭**
2. ![new](https://github.com/user-attachments/assets/3481a680-f677-403b-be8c-1fe59d5aa7cb)

3. **Repository 이름 입력**
4. **Public/Private 선택**
5. **README.md 파일 생성 체크**
6. **Create repository 버튼 클릭**
   
![create_repository](https://github.com/user-attachments/assets/8c2eb16b-8dfc-465a-88cd-d35770d12df0)

___


# Markdown 문법 정리
 
### 📌 제목 (Headers)

# H1  
## H2  
### H3  
#### H4  
##### H5  
###### H6

### 📌 글자 꾸미기

**굵게**   

*기울임*    

~~취소선~~  

`인라인 코드`  

> 인용문

### 📌 이미지 가져오기
1. 이미지 캡쳐 후 다른 이름으로 저장 -> 이미지 드래그
2. Ctrl C + Ctrl V 이용해서 붙이기
3. url 복사하고 붙여넣기 이용
4. ![image](https://github.com/user-attachments/assets/0ccccaff-a940-4b5f-b55a-95c8e436e8ea)



### 📌 Task Table
| 기능 | 완료 여부 |
|------|------------|
| 로그인 | ✅ |
| 회원가입 | ❌ |












___


# Colab 기초
![image](https://github.com/user-attachments/assets/7bfdb17b-9994-43e7-8e00-d3d4c07b5fb1)

## 📌 Colab 노트북 내에서 GitHub에 저장하기

Google Colab에서 작업한 내용을 GitHub 저장소에 직접 저장할 수 있습니다.

### 🔄 저장 방법

1. 상단 메뉴에서 **`파일(File)` → `GitHub에 사본 저장(Save a copy in GitHub)`** 클릭  
2. 로그인된 GitHub 계정을 통해 Colab이 저장소 접근 권한 요청  
3. 저장소(repository), 브랜치(branch), 파일 경로(path), 커밋 메시지를 입력  
4. **[확인(Save)]** 버튼 클릭 → GitHub에 `.ipynb` 파일이 업로드됨

---

### ✅ 예시 화면
![image](https://github.com/user-attachments/assets/71aa4189-e76c-4f14-898b-f08b866f2441)

1. 웹 브라우저(chrome) 열고 **Colab 웹사이트 접속하기** :
   이 주소를 참조하세요. -> [Colab 바로가기] (https://colab.google)

2. **New Notebook** 클릭하기

3.
   ![image](https://github.com/user-attachments/assets/e4d89e2b-810b-4a6c-b100-47f8998c7243)

   (1) 노트 이름 변경 -> (2) 런타임 클릭 -> (3) 런타임 유형 변경 클릭 -> T4 GPU로 변경 후 저장

   ![image](https://github.com/user-attachments/assets/e9da7907-cad2-4a13-a552-a6630aec9413)

4.
   ![image](https://github.com/user-attachments/assets/38331632-fcec-4844-bc1f-c0d73831dda0)
   빈칸에 python 코드 작성 후 디버깅 가능

5.
   ![image](https://github.com/user-attachments/assets/60c876a6-08ae-4f49-aeaf-ee81e5f39221)
   왼쪽 상단의 파일 클릭 -> 'GitHub에 사본 저장' 클릭하면 GitHub에 생성됨

___

## 2. About Python3
- [Python basic](docs/python.md)

## 3. Data Structure / Data Science
- [데이터 구조 개요](docs/data_structures.md)
- [Pandas](docs/pandas.md)
- [Numpy](docs/numpy.md)
- [Matplotlib](docs/Matplotlib.md)

## 4. Machine Learning
- [Machine Learning Basic](docs/ml_basic.md)
- [모델 훈련 및 평가](docs/ml_test.md)

## 5. OpenCV
- [OpenCV Basic](docs/OpenCV_basic.md)
- [이미지 처리](docs/image_test.md)

## 6. CNN (Convolution Neural Network)
- [CNN_Basic](docs/CNN_basic.md)
- [CNN_자율주행 관련 코드](docs/cnn_test.md)

## 7. Ultralytics
- [Ultralytics_Basic](docs/Ultralytics_basic.md)
- [YOLOv8](docs/YOLOv8_test.md)
- [YOLOv12](docs/YOLOv12_test.md)

## 8. TensorRT vs PyTorch 
- [PyTorch_Basic](docs/PyTorch_basic.md)
- [TensorRT](docs/TensorRT_test.md)
- [YOLOv12](docs/YOLOv12_test.md)

## 9. TAO Toolkit on RunPod
- [TAO_사용법](docs/TAO_install.md)
- [TAO_Toolkit](docs/TAO_Toolkit.md)

## 10. 칼만필터, CARLA, 경로 알고리즘
- [kalman](docs/kalman.md)
- [CARLA_simulator](docs/CARLA.md)

## 11. ADAS & (ADAS TensorRT vs PyTorch)
- [adas_basic](docs/adas_basic.md)
- [TensorRT vs PyTorch 비교](docs/vs.md)

---

<details>
<summary>📁 <b>docs 폴더와 빈 .md 파일 자동 생성하기 (Python 스크립트)</b></summary>

```python
# Python 스크립트: docs 폴더 안에 필요한 .md 파일 자동 생성
import os

# 만들 폴더 이름
folder_name = "docs"

# 생성할 .md 파일 목록
file_names = [
    "python.md",
    "data_structures.md", "pandas.md", "numpy.md", "Matplotlib.md",
    "ml_basic.md", "ml_test.md",
    "OpenCV_basic.md", "image_test.md",
    "CNN_basic.md", "cnn_test.md",
    "Ultralytics_basic.md", "YOLOv8_test.md", "YOLOv12_test.md",
    "PyTorch_basic.md", "TensorRT_test.md",
    "TAO_install.md", "TAO_Toolkit.md",
    "kalman.md", "CARLA.md",
    "adas_basic.md", "vs.md"
]

# docs 폴더 생성
os.makedirs(folder_name, exist_ok=True)

# 각 파일 생성
for name in file_names:
    file_path = os.path.join(folder_name, name)
    with open(file_path, 'w', encoding='utf-8') as f:
        f.write(f"# {name.replace('.md','').replace('_', ' ').title()}\n\n_This is a placeholder file._")

print("✅ docs 폴더와 .md 파일들이 생성되었습니다!")

