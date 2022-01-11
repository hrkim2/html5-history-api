\* SPA가 한페이지로 웹을 구현할 수 있는 비결 \*  
### history.`pushState`
* 요청 주소를 주소 목록에 추가.  
▶브라우저 뒤로가기 생성
```javascript
history.pushState(dataObject, "page title", "url");
```
### history.`replaceState`
* 현재 주소를 요청 주소로 대체  
▶브라우저 뒤로가기 생성되지 않음
```javascript
history.replaceState(dataObject, "page title", "url");
```
* dataObject는 history.state에 저장됨  
