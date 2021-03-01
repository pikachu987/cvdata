|이미지 피커|
|---|
|<video controls autoplay width="250"><source src="./html.mp4" type="video/mp4"/></video>|

- DocumentType.html이 정확하지 않아서 NSAttributedString을 정규식으로 html형식으로 변경
- html형식을 NSAttributedString으로 변경중 DarkTheme 적용
- 배경색, 글자색이 있는 상태에서 \n(엔터)가 들어왔을때 색이 초기화 되는 현상을 제거하려고 NSTextStorage 커스텀