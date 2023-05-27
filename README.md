# js_문자이펙트 

animation: blink .5s infinite, typing 3s steps(22);<p></p>
/* typing 2s steps(22) : 3초에 걸쳐서 22번 동작하게한다 */<p></p>
white-space: nowrap;<p></p>
overflow: hidden;<p></p>
/* 텍스트가 한줄로 출력되게 하는 white-space */<p></p>
/* 부모영역이 충분하지 않으면 감춘다 */<p></p>
<br></br>
@keyframes blink{<p></p>
50%{border-color: transparent;}<p></p>
/* 0초에서~0.25초까지는 흰색에서 투명한색으로 변한다. */<p></p>
/* 이게 커서가 깜빡이는것처럼보인다. */<p></p>
}<p></p>
<br></br>
@keyframes typing{<p></p>
from{width: 0;}<p></p>
to{width: 485px;}<p></p>
        /* 0픽셀 476픽셀로 22번 동작한다. */<p></p>
    }
