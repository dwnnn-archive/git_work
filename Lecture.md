# 확장자명
- yml도 되는데, 공식 확장자명은 yaml임.

# 시작
git init (해당 파일에서 실행하겠다)
git status (저장된 항목 확인)

# git에 올라가지 않게 하기
.gitignore 파일을 만들기
 - 이 파일에 이름이 적힌 파일은 git에 저장되지 않음 (탐색기에서 이름이 흐리게 변함)

# git add .
 - 전체 저장

# git commit -m "Initial Commit"
변경 버전 등록하기
Initial Commit 부분은 커밋할 버전의 이름

# Source Tree
커밋 과정을 이쁘게 보여주는 꽁짜 앱~
(git log와 비슷함)

# git reset --hard d6e72eb
(hard는 싹 다 없애버리겠다는 말, 여기서는 LG Twins(d6e72eb)까지만 남겨놓겠다는 말임)

# HEAD 바꾸기
git branch (지금 있는 branch 확인)
git branch add-coach (add-coach라는 branch 생성)
git switch add-coach (add-coach branch로 HEAD바꾸기)
git switch -c 'new-teams' (생성과 변경을 한번에!)

# git merge

# git rebase (branch_name)
branch가 new-temas인 상태로 git rebase main을 하면 main이 (branch_name)의 변경사항을 가져옴
rebase는 비추천(꼭 필요하지 않으면 rebase보다는 merge를 사용)

# git push origin main
github로 보낼 수 있도록 git으로 보낼 때 사용
origin main은 기본적으로 있는 폴더
처음에만 origin main을 써주면 다음부터는 git push만 하면 됨

# 패치를 하면 pull 해 올 것이 있는지 확인하는 것임.
pull 해 올 게 있으면 origin이 붙은 변경기록이 main의 위에 붙음(SourceTree)