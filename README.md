# Checklist project

### Branches
1. **main**
   - 프로젝트의 기본 버전을 담당할 브랜치

### Front
1. index.html, index.css
   - 직원용 체크리스트 관리용 페이지
2. login.html, login.css
   - 로그인용 페이지
3. signUp.html, signUp.css
   - 회원가입용 페이지
4. manage.html
   - 사장 및 관리직을 위한 체크리스트 관리용 페이지
   

### Function
1. signUp
   - 아래의 요소들을 입력받아 DB에 저장
   - (필수)사업장의 key가 될 아이디-비밀번호, 사장의 key가 될 직원번호
   - (선택)체크리스트를 공유할 포지션의 key가 될 직원번호
2. login
   - 사업장의 아이디-비밀번호와 직원번호를 같이 입력받음
   - 자동로그인 기능을 체크했다면 모든 정보를 자동으로 입력해줌
   - 아이디-비밀번호가 틀릴 경우, 둘 중 하나가 틀렸다는 알림 출력
   - 직원번호가 틀릴 경우, 직원번호가 틀렸다는 알림 출력
3. index(직원용 메인 페이지)
   - 확인사항(toDoList): 본인의 확인사항을 체크, 수정, 삭제, 추가할 수 있음
       - 본인보다 직급이 높은 사용자가 설정한 확인사항은 수정 및 삭제할 수 없음
   - 전달사항 및 건의사항: 사항을 추가, 삭제, 수정할 수 있음
       - 수정 및 삭제는 본인이 작성한 사항에만 가능함
       - 사항 추가시 본인의 이름을 기입할 수 있음(미기입시 포지션만 공개)
   - 로그아웃: 로그인 페이지로 돌아옴
4. manage(사장 및 관리직 메인 페이지)
   - 체크리스트 확인 및 관리: 포지션별 현재 체크리스트 현황을 확인할 수 있으며, 추가 및 수정, 삭제 가능
       - 수정 및 삭제는 본인보다 직급이 높은 사용자가 설정한 것에는 불가능함
   - 전달사항 및 건의사항: 사항을 추가, 삭제, 수정할 수 있음
       - 직원(index)의 경우와 동일함
   - 로그아웃: 로그인 페이지로 돌아옴
   
   
   
