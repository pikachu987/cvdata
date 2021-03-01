|이미지 피커|여러장 선택|비디오 피커|
|---|---|---|
|<video controls autoplay width="250"><source src="./single_gallery.mp4" type="video/mp4"/></video>|<video controls autoplay width="250"><source src="./multi_gallery.mp4" type="video/mp4"/></video>|<video controls autoplay width="250"><source src="./video.mp4" type="video/mp4"/></video>|

|이미지&비디오|이미지 뷰어|시스템 카메라 촬영후 편집|
|---|---|---|
|<video controls autoplay width="250"><source src="./chat.mp4" type="video/mp4"/></video>|<video controls autoplay width="250"><source src="./update.mp4" type="video/mp4"/></video>|<video controls autoplay width="250"><source src="./systemVideo.mp4" type="video/mp4"/></video>|

<br><br>

- CIDetector를 사용해 얼굴로 인식하는 부분의 좌표 체크
- CIFilter를 사용해 얼굴 부분 블러처리
- CIFilter를 사용해 이미지 밝기 조절
- CAShapeLayer를 사용해 이미지, 비디오 자를 frame만 표시
- AVAssetExportSession를 사용해 비디오 영역 자르기, 시작 & 끝 시간 자르기, 회전, 화질, 음소거 수정