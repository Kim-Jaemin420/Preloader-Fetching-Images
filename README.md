# Preloader Fetching Images  

**프리로더란?**  

> A preloader — or what some call a loading screen — is the what you see on some sites before the main content of the web page is loaded. ... Their main purpose is to entertain site visitors while the actual content of the page is still loading in the background.  

> 프리로더란 사용자가 웹 페이지를 방문했을 때, 메인 컨텐트가 나오기 전에 보이는 것이다. 프리로더의 목적은 페이지의 진짜 컨텐트가 로딩되기 이전에 사이트 방문자를 즐겁게 해주는 것에 있다. pinterest를 상상하면 적절할 것이다.  


이 프로젝트의 목적은 이미지를 api로 가져와 프리로더를 자연스럽게 만드는 것이 목적이다. 그런데, 이 프로젝트는 이미지가 자연스럽게 로드되지 않는다. 이유는, 각각의 이미지들이 모두 같은 시간에 도착하지 않아서이다.   

fetch를 수행하는 함수 내부에서 setTimeout을 사용한 이유는 단순히 로딩 svg를 보여주기 위함이다. 다음 repo에서 더 매끄러운 프리로더를 구현해 놓았다.  

