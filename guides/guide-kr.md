# 기여 가이드

## 기여를 위한 단계별 가이드

기본적으로 이 프로젝트에 기여하는 단계는 다음과 같습니다:

### 1단계: 저장소 포크하기

1. **저장소 포크하기**

   Sandbox 저장소 페이지 오른쪽 상단의 "Fork" 버튼을 클릭하여 저장소를 포크합니다.

2. **포크한 저장소 복제하기**

   ```sh
   git clone https://github.com/your-username/sandbox.git
   ```

   `your-username`을 GitHub 사용자 이름으로 바꿉니다.

3. **프로젝트 디렉토리로 이동하기**

   ```sh
   cd sandbox
   ```

### 2단계: 이슈 만들기

1. 저장소의 [이슈](https://github.com/your-username/sandbox/issues) 탭으로 이동합니다.
2. "New issue" 버튼을 클릭합니다.
3. 이슈 템플릿에 관련 세부 정보를 입력하고 제출합니다.

### 3단계: 저장소 복제

다음 명령어를 사용하여 포크된 저장소를 로컬 머신에 복제합니다:

```sh
git clone https://github.com/your-username/sandbox.git
```

`your-username`을 GitHub 사용자 이름으로 바꿉니다.

### 4단계: 브랜치 생성

기능 추가나 버그 수정을 위한 새로운 브랜치를 만듭니다:

```sh
git checkout -b feature-branch-name
```

`feature-branch-name`을 브랜치의 설명적인 이름으로 바꿉니다.

### 5단계: 변경 사항 적용

새 브랜치에서 필요한 변경 사항을 적용합니다.

### 6단계: 변경 사항 커밋

의미 있는 커밋 메시지와 함께 변경 사항을 커밋합니다:

```sh
git add .
git commit -m '의미 있는 커밋 메시지 추가'
```

### 7단계: 변경 사항 푸시

브랜치를 포크된 저장소에 푸시합니다:

```sh
git push origin feature-branch-name
```

### 8단계: 풀 리퀘스트 만들기

1. GitHub의 원본 저장소로 이동합니다.
2. "Compare & pull request" 버튼을 클릭합니다.
3. PR 템플릿에 관련 세부 정보를 입력하고 제출합니다.

### 9단계: 풀 리퀘스트 검토 및 병합

1. PR이 검토되고 승인되면 병합할 수 있습니다.
2. "Merge pull request" 버튼을 클릭합니다.
3. 병합 후 저장소를 깨끗하게 유지하기 위해 브랜치를 삭제합니다.
