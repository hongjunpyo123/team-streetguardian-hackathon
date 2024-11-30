# Street-Guardian Project

## 프로젝트 소개
본 프로젝트는 긴급도 점수 산정 시스템에 관한 것으로서, 상세히 설명하면 LLM 모델을 활용하여 온라인 게시판의 게시글에 가중치를 통한 긴급도를 자동으로 평가하고 정렬하는 시스템, 알고리즘에 관한 것이다.

### 프로젝트 설명
이 프로젝트는 다음과 같은 기능을 제공합니다:
- **기능 1**: 랭크 시스템을 통한 경쟁
- **기능 2**: 긴급도 산정 시스템으로 도움이 필요한 미션 게시글을 상단에 노출
- **기능 3**: 미션 클리어 시 긴급도 가중치에 따라 포인트 지급

## 주요 기능
### 기능 1
- **기능 설명**: 유저가 미션 게시판에서 미션 클리어 시 일정량의 포인트를 지급받게 되며, 보유한 미션 포인트에 따라 상대적인 랭크를 부여받게 됨

### 기능 2
- **기능 설명**: 미션 게시판의 미션게시글은 긴급도 산정 시스템에 따라 긴급도를 평가하고 내림 차순으로 정렬시켜 상단에 노출
- 
### 기능 3
- **기능 설명**: 상단에 노출된 미션일 수록 긴급한 도움이 필요한 상황임을 의미하며, 유저가 이에 기여할 시 더 많은 포인트를 지급받게 됨

## 기술 스택
- **Frontend**: HTML, CSS, JavaScript, Mustach
- **Backend**: Spring Boot, Java
- **Database**: MySQL
- **기타**: InteliJ, Git

## 특허 정보
### 특허 출원 번호
- **특허 출원 번호**: 10-2024-0174861

### 특허 출원 날짜
- **특허 출원 날짜**: 2024년 11월 29일

### 특허 제목
- **특허 제목**: 긴급도 점수 산정 시스템{Emergency Score Calculation System}

### 특허 설명
이 특허는 우리 프로젝트의 핵심 기술을 보호하며, 다음과 같은 내용을 포함합니다:
- **특허 내용 요약**: 일반적으로 사회봉사, 재난, 긴급 구조, 피해자 지원 등 긴급 상황을  효과적으로 판별하고 대응할 수 있는 시스템 및 방법이 제공되지 않고 있다.
특히, 특정 키워드가 포함된 게시글의 위험도나 긴급도를 점수화하여 긴급도가 높은 순서대로 게시글을 정렬함으로써 사용자들이 신속하게 중요한 정보를 확인할 수 있도록 돕는 기술에 관한 선행기술은 확인되지 않고 있다.

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Street-Guardian Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Street-Guardian Project</h1>
    </div>
</body>
</html>
