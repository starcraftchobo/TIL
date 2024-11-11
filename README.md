# TIL
## 요런 내용을 넣어보자!
- 어떤걸 배웠는지
- 어떻게 활용했는지
- 어떤 문제가 발생했는지
- 어떤걸 시도했는지
- 어떻게 해결했는지
- 새로 알게된점
# 규칙
- 절대 **이해하지** 못한 내용은 대충 적지 않기!

# 작성법
- 마크다운 형식으로 작성
----

# 지금까지 배운것
## git활용법
1. working directory, staging area, repository에 대한 개념 이해
   - working directory = 현재 작업중인 영역
   - staging area = 로 update할 녀석들을 선별하는 장소
   - repository = staging area의 녀석들을 으로 최종 저장. 수정 사항을 알기쉽게 텍스트 작성 가능
1. `git `
1.

로컬 레포지토리 등록
깃 이닛
깃 애드
깃 커밋

원격 레포지토리 연결(repo in github)
깃 remote add origin link
git push/pull/clone
-v
    config
    --list, --global

이외의 명령어
git status
git ls(-a)
git log(--oneline)
git rm
git 



## CS는 운영체제와 네트워크 중심

## 포폴 관리
 2학기 플젝 깃허브 관리
 플젝 관련 기술적인 요소 숙지
 어떤 문제에 관심이 있고 어떻게 해결해왔는지
 플젝 주제가 이어지면 좋음

## 기타
 개발 관련 기획, 딴 길로 새기도 굳

## 파이썬 문법 정리
###24.11.11
-얕은복사 깊은복사
 1. 얕은복사(y = copy.copy(x))
    - 얕은 복사는 원본의 메모리 참조 -> 한놈만 바꿔도 다른놈들 바뀜
    - mutable한 녀석들에 한해서 발생
    - 피하기 위한 방법은 깊은 복사나 mutable 객체 안의 값을 다른 변수에 직접 재할당
 2. 깊은 복사(y = copy.deepcopy(x))
    - 깊은복사는 새로운 객체의 '사본'을 생성해 새로운 객체에 삽입
    - 기본적으로 재귀적으로 동작해 순환 참조의 경우 문제가 생길수 있으나
    - memoization을 통해 해결한다는데 이건 차차 이해하자
 3. 얕깊 확인
    - is 키워드를 쓰면 확인가능
    - 얕은복사일경우
    - a == b //True
    - a is b //False
