# float속성의 html을 짠이유

1. img태그에 스크린 리더가 읽을 수 있게 aria-label를 주었습니다.
2. span요소에 title을 주어 마우스를 올렸을때 온라인인지 오프라인인지 설명을 주었다. img를 감싼 span에 float을 주어 나열하였습니다.
3. div를 주어 온라인 오프라인 아이콘을 만들어 postion:absolut를 주어 div기준으로 위치를 지정했다.그후 div#online에 width를 주었다. width와 height를 주어 화면을 늘려도 움직이지 않게 고정하였습니다.

# flex의 html을 쓴이유

1. float과 똑같은 이유로 img를 span으로 묶었다. 하지만 flex의 경우 이미지가 슬비썜이 하신것과 다른 순서로 나온다. 왜인지 모르겠다.
2. flex는 float보다 유동적이므로 flex-direction을 주어 가로열로 주고 flex-wrap을 사용하여 .container가 좁아질때 줄이 바뀌도록 바꿔주었습니다. justify-content를 space-evenly로 주어 첫번째 요소와 마지막 요소 간격을 기준으로 컨테이너 요소들의 간격을 같게 하였습니다.
3. position:absolute를 주어 .container를 기준으로 위치를 지정했습니다.

# 공통점

absolute를 주어 부모를 기준으로 top과 right left를 주어 위치를 주었습니다.
온라인과 오프라인에 gray green 클래스를 주어 background에 컬러값을 주었습니다
border값을 주어 테두리를 만들었습니다.

# 궁금한점

왜 사진이 순서대로 안나올까요?
