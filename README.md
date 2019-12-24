# git-practice

## VCS: Version Control System

> 필요한 이유
> 1. 변경점 관리
> 2. 버전 관리
> 3. 백업 & 복구
> 4. 협업


## 중앙집중형 VCS

> 중앙 서버에 모든 버전을 두고 처리한다.
>
> 충돌을 완전 없앨 수는 없고 최소한으로 합의를 해야한다.


## 분산형 VCS

> 모든 버전을 가지고 있는 저장소를 가지고 일을 한다.
>
> 모든 사람에게 버전이 있기 때문에 안전하다.
>
> 중앙집중형 -> 분산형


## Git 장점

1. 빠른 속도
2. 단순한 구조
3. 비선형적인 개발(수천 개의 동시 가발적인 브랜치)
4. 완벽한 분산
5. Linux 커널 같은 대형 프로젝트에도 유용할 것(속도, 데이터 크기 면에서)


## Git 단점

1. 어렵다.
2. 대용량 바이너리 파일 관리가 어렵다.
> 모든 사용자가 파일의 full change history를 가지고 있기 때문에 용량이 매우 커진다.


## 명령어

> commit - 스냅샷을 찍어 저장한다.
>> staged / unstaged로 구분되어 진다.
>
> rebase
>> branch를 최상위버전에 옮기는 것
>> rebase는 SourceTree에서 잦은 버그가 있기 때문에 command가 더 편하다.
>> git rebase -i "새로운 베이스 위치"
>
> cherry-pick
>> 다른 branch의 commit을 현재 branch에 반영
>
> git stash
>> 임시 백업용 저장공간을 만든다.
>> 작업을 하고있을 때 commit은 하지 않고, branch를 옮길 때 사용



