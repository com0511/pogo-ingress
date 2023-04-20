# pogo-ingress

## [iPhone]

>##### 1. 계정생성
>- 앱스토어에서 'Ingress Prime'을 설치하고 구글계정으로 가입을 한 후 튜토리얼을 완료한다.
>##### 2. IITC-Mobile 앱 설치
>- 실제 사용할 앱으로 앱스토어에서 'IITC-Mobile'을 설치한다.
>##### 3. 플러그인 설치
>- IITC-Mobile을 실행하고 우측 상단 톱니모양(Settings) > IITC Plugins > User Scripts 를 누르고  
>  https://gist.githubusercontent.com/5310/c216c40cf6d34834c9cfaad0d820ae4d/raw/948ebdb9f3640d33fabeb13e4f566673170d5dbe/s2check.user.js
>  위 주소 입력한 후 OK를 눌러준다.
>  User Scripts 목록에 's2check.user.js'라는 항목이 생긴다면 정상적으로 설치된 것.
>##### 4. 플러그인 설정
>- User Scripts에서 뒤로가기를 하여 Plugins 목록에서  
>  Layer > IITC plugin: Portal Names 와 Pogo Tools, PoGOHWH 두 가지를 체크해준다.
>##### 5. 맵 설정
>- Settings을 벗어난 후 맵 좌측 상단 Menu에 들어간다.
>- Base Layers 탭에서 Google Default Ingress Map 을 체크
>- Overlay Layers 탭에서 Fields, Links 체크 해제
>##### 6. 완료



## [PC]
>##### 1. 계정생성
>- 앱스토어에서 'Ingress Prime'을 설치하고 구글계정으로 가입을 한 후 튜토리얼을 완료한다.
>##### 2. TemperMonkey 설치
>- 구글 플러그인 TemperMonkey를 설치한다.  
>  https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ko
>##### 3. TemperMonkey 플러그인 활성화
>- 크롬 우측 상단에 퍼즐 조각 모양을 눌러 설치한 TemperMonkey가 플러그인 아이콘에 노출되도록 한다.
>##### 4. 플러그인 설치
>- https://iitc.me/desktop/ 에서 플러그인을 다운로드 한다.(아래 링크를 눌러도 됨)  
>  https://static.iitc.me/build/release/total-conversion-build.user.js 또는  
>  https://github.com/com0511/pogo-ingress/blob/main/pc/total-conversion-build.user.js
>- 14, 17 셀 플러그인 설치
>  https://github.com/com0511/pogo-ingress/blob/main/pc/level14and17cells.user.js
>- TemperMonkey가 정상적으로 설치가 되었다면 위 파일들을 다운로드 할때 파일을 내려받는 형태가 아닌  
>  TemperMonkey에 설치가 될 것이다. 
>- 혹시라도 위 과정이 잘 안되서 TemperMonkey에 바로 설치가 되지 않고 파일로 내려받는 형태라면  
>  우측 상단 TemperMonkey 플러그인을 클릭하고 새 스크립트 만들기 > 설치된 유저 스크립트에  
>  위에 다운받은 파일 2개를 넣어준다.(drag and drop)
>##### 5. 인그레스 맵 설정
>- https://intel.ingress.com/intel 웹으로 이동을 하면 TemperMonkey 플러그인에 2라는 숫자가 표시된다.  
>  (위 과정들이 정상적으로 되었다면)
>- 우측 상단에 네모가 겹쳐있는 흰색 아이콘이 있다. 그걸 누른 후 Google Default Ingress Map 체크, Fields/Links 체크 해제
>##### 6. 완료

