# js_문자이펙트 

animation: blink .5s infinite, typing 3s steps(22);<p></p>
/* typing 2s steps(22) : 3초에 걸쳐서 22번 동작하게한다 */
white-space: nowrap;
overflow: hidden;
/* 텍스트가 한줄로 출력되게 하는 white-space */
/* 부모영역이 충분하지 않으면 감춘다 */

@keyframes blink{
50%{border-color: transparent;}
/* 0초에서~0.25초까지는 흰색에서 투명한색으로 변한다. */
/* 이게 커서가 깜빡이는것처럼보인다. */
}

@keyframes typing{
from{width: 0;}
to{width: 485px;}
        /* 0픽셀 476픽셀로 22번 동작한다. */
    }
