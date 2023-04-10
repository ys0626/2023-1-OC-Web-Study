외부 링크: https://therapeutic-donut-9e2.notion.site/GDSC-3-ff89a4bf7cd449019d70d9c63278b5c0

# GDSC 기초 웹 스터디 3주차 과제

# github으로 협업 하는 방법 맛보기 후기

우선… 정말 정말 어려웠다… 중간에 포기하고 싶을 정도로… 그래도 서치와 친구의 도움을 받아 어떻게든 rp를 완료했다. 정말 너무 힘들었는데 감격스럽게도 완벽하다는 답이 왔다. 정말 다행이다…

# 1. github에서 fork 해오기

협업을 하기 위해서는 다른 사람의 레포지토리를 가져올 수 있어야 한다. 그러기 위해서는 fork를 통해 레포지토리를 자신의 remote repository로 옮겨와야 한다. fork 해오고 싶은 레포지토리에 들어가 상단에 있는 fork 버튼을 통해 하면 된다.

# 2. 가져온 레포지토리를 clone 해 로컬로 불러오기

remote repository로 가져온 것을 로컬로 불러오고 싶다면 clone을 쓰면 된다. 우선 자신의 핸들명으로 브랜치를 만들라는 조건이 있으므로 git checkout -b [branch name] 명령어를 통해 브랜치를 새로 만들어준다. 이 명령어를 통해 브랜치를 새로 만들고 동시에 그 브랜치로 전환을 바로 할 수 있다. 혹시 모르니 git branch checkout 으로 한 번 확인을 해보자. 아마 already~ 하면서 이미 그 브랜치에 있다고 알려줄 것이다. 그 다음 git clone [repository url]을 하면 수행된다. 여기에서 명심할 것은 (이 부분에서 굉장히 오래 걸렸는데) clone 된 repository 폴더로 이동을 해줘야 한다. 터미널에 cd [폴더 주소]로 이동해주면 된다. 그 다음 폴더 내에 새 폴더를 만들어주고 그 안에서 이름 markdown 문서를 만들어준다.

# 3. remote repository로 push 하기

필요한 것을 만들어줬으니 push 해준다. 우선 git add . 을 하고 git commit -m Feat : [내용] 을 입력해 커밋 메세지 컨벤션을 지켜준다. 다음 git push origin [branch name] 을 하여 push를 해 remote repository로 올린다.

# 4. PR하기

드디어 PR을 할 수 있다! push를 하고 나면 Pull Request 를 할 것이냐는 버튼이 생기는데 그것을 눌러주면 된다. 그 전에 생성된 branch를 확인하고 눌러 변경해준다. 전송되는 곳과 받는 곳의 repository가 원하는 곳과 다르지는 않은지 확인해주고 Creat Pull Request를 해주면 끝이다.
