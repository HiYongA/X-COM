1. <strong>폴더 구조 잡기</strong> <br/>
   폴더 구조와 동일한 [username]으로 쓸 수 없게 해야한다.
   
2. <strong>레이아웃 잡기</strong> <br/>
   로그인 전, 후로 구분짓기
   폴더명: (afterLogin), (beforeLogin)
   소괄호()의 역할: 그룹을 만들 수 있고, 주소창에 관여하지 않는다.
   
3. <strong>layout.tsx와 template.tsx의 차이</strong> <br/>
   layout은 페이지를 넘나들 때 리렌더링이 안된다.
   template은 페이지를 넘나들 때 리렌더링이 된다.
   
4. <strong>Parallel Routes, Intercepting Routes을 함께 쓰면 기존 화면에 위에 모달창을 띄울 수 있다.</strong> <br/>
   Parallel Routes: page.tsx 위에 모달을 띄우고 싶을 때 사용 -> @modal폴더 만들기
   Intercepting Routes: 다른 페이지에서 링크를 통해 주소에 접근했을 때 가로채기 라우터가 실행 -> (.)i폴더 만들기
    
5. <strong>프라이빗 폴더(언더바_)</strong> <br/>
   여러 곳에서 공통으로 사용되는 파일이 있는 경우, 공통 부모를 찾아 _component폴더를 만들어 넣어둔다.
   
6. <strong>주소창에 나타나지 않는 세 가지 요소</strong> <br/>
   - 그룹 지어주는 그룹폴더: 레이아웃을 두는 역할
   - Parallel Routes: 한 화면에 2개의 페이지를 동시에 보여주는 역할
   - 프라이빗 폴더: 폴더 정리용
  
7. <strong>서버 컴포넌트만 클라이언트 컴포넌트를 import할 수 있다.</strong> 
