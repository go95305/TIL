TIL
===

today i learned

### <strong>[21.03.06]</strong>
#### --allow-unrelated-histories
로컬 저장소와 원격지의 저장소의 기록(History)을 비교했을 때 소스코드의 차이가 심한 저장소의 경우, 병합 오류가 날 것을 대비하여 오류 메시지를 띄우는 것

<br/>
### <strong>[21.03.12]</strong>
#### Front에서 바로 DB접근을 안하는 이유
- DB Connection Pool의 포화
- 해킹 

<br/>

### <strong>[21.03.14]</strong>
#### Remote branch 이름 변경하기
1. 기존 Local 브랜치(git에 등록되있는)명 변경
> git branch -m oldbranch newbranch
2. remote repository에 존재하는 기존 브랜치 삭제
> git push origin :oldbranch
3. 새로운 브랜치를 repository에 추가
> git push origin newbranch
