<h1>SpeedQuiz Project</h1>
<ul>
  <li>프로젝트 개요 : Browser 환경 JavaScript 기반의 SpeedQuiz PGM 제작</li>
  <li>개발기간 : 2018-12-14 ~ 2018-12-21 (8일)</li>
  <li>인원 : 5명</li>
  <li>개발환경 : JavaSript, HTML5, CSS, EditPlus</li>
</ul>
<table>
  <tr>
    <td align="center"><b>UI</b></td>
    <td align="center"><b>상세 설명</b></td>
  </tr>
  <tr>
    <td>
      <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMjAw/MDAxNTU3MjE1NTI2NzM1.zV0TLlQn3iWqm1tC5Ne5MWWzcLiIZXOJiel2jzTNI4Ig.TuAdKGUp-ax1EWp-_8KBomLGPPjzlv90K_H1SF3TyoAg.PNG.phh_92/main_%ED%99%94%EB%A9%B4.png?type=w2" width="350px"/>
    </td>
    <td>
      <ul>
        <li>SpeedQuiz 시작 화면</li>
        <ol>
          <li>Start Button Click 시 게임 진행 화면으로 넘어감</li>
        </ol>
      </ul>
    </td>
  </tr>
   <tr>
    <td>
      <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMjc5/MDAxNTU3MjE1NTI3NTQ4.OcUvzOFDGMvD21R0s7i-C7fZvWse41tjW8tjQ2oAyCAg.XsFQi8RlDy7LOognagRwsM5HQ1D0VKiXHf9znV3_ffUg.PNG.phh_92/Quiz_%ED%99%94%EB%A9%B4.png?type=w2" width="350px"/>
    </td>
    <td>
      <ul>
        <li>SpeedQui 게임 화면</li>
        <ol>
          <li>조 추첨 Button 을 눌러 참여할 Team 개수를 입력</li>
          <li>입력받은 수의 범위에서 난수 출력하여 게임을 진행할 조를 추출</li>
          <li>게임을 진행할때 조 추첨을 하지 않으면 게임이 진행 될 수 없음</li>
        </ol>
      </ul>
      <table style="border:1px solid black">
        <tr>▶ 조 추첨 진행 화면</tr>
        <tr>
          <td>
            <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfNTYg/MDAxNTU3MjE1NTU0MjQ2.FDE-h8vYDDki3UQKubHzIl3C0LDGZMqRcObQqjpO92og.8tG-xNzbjP9yweG6mZPf3htTje0lJ0a3q55CYlCCgB4g.PNG.phh_92/%EC%A1%B0_%EC%B6%94%EC%B2%A8.png?type=w2" width="250px"/>
          </td>
          <td>
            <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMjM1/MDAxNTU3MjE1NTU1Mjg3.XzTxFpJi_WuAfPhyCqLZzPJcVoJ0oKLT5wDqBej0a6wg.ZFhzKCSHSVYPi-XMuZwh41NFb_AiRZPRmJs6azFaoTIg.PNG.phh_92/%EC%A1%B0%EC%B6%94%EC%B2%A8_2.png?type=w2" width="250px"/>
          </td>
        </tr>
      </table>
     <tr>
      <td>
        <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMTA4/MDAxNTU3MjE1NTI4MjM4.c0Yl-uRNh1YGY6kx2SxGbRCMk1BpYe4nJof4e-uqawwg.waoN3VmXdd5fl5VrhnuOP7yfh3zeFMCNw8La9kjgA2kg.PNG.phh_92/Score.png?type=w2" width="350px"/>
      </td>
      <td>
        <ul>
          <li>게임 진행 화면</li>
          <ol>
            <li>게임이 시작되면 타이머가 가동된다, 타이머의 시간은 Code 내에서 수정이 가능하다</li>
            <li>문제를 맞힐시 다음(정답) Button 을 누른다. Score 는 10점씩 증가한다.</li>
            <li>정답 처리된 문제는 다시 출제되지 않는다.</li>
            <li>Pass Button 을 누를시 Score 는 증가하지 않으며 문제가 넘어간다</li>
          </ol>
          <br>
          <table>
            <tr>
              <td>
              ▶ 시간 초과 경고화면
              </td>
            </tr>
            <tr>
              <td>
                <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMTg5/MDAxNTU3MjE1NTMwNDk2.CJRqh90cjNtNjd97TCPXrPWPOSOeJeWAxxMcV2DAbR4g.d15sivBul78yjLGhm9PeR1Mjx07OPx-M9DCp6Hs914og.PNG.phh_92/%EC%8B%9C%EA%B0%84%EC%B4%88%EA%B3%BC_%EA%B2%BD%EA%B3%A0_%ED%9A%A8%EA%B3%BC.png?type=w2" width="250px"/>
              </td>
            </tr>
            <tr>
              <td>
                <ol>
                  <li>시간이 10초 이하로 남게 된다면 위 이미지와 같이 화면이 붉은색으로 깜빡이게된다.</li>
                </ol>
              </td>
            </tr>
            <tr>
              <td>▶ 시간 초과 화면</td>
            </tr>
            <tr>
              <td>
                <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMjQ0/MDAxNTU3MjE1NTI5MDEw.wDrTxAUE-8uLWBQM3XOFF64Aj-9MwDbwmoDL5AgLSzYg.7vNTZ25_hqWPrHxnQllNnAzjW71WZIVv_pKqq6o55yIg.PNG.phh_92/Timeover_%ED%99%94%EB%A9%B4.png?type=w2" width="250px"/>
              </td>
            </tr>
            <tr>
              <td>
                <ol>
                  <li>시간이 초과되면 위 이미지와 같이 해골 이미지가 화면을 돌아다니는 효과가 나타난다.</li>
                </ol>
              </td>
            </tr>
          </table>         
        </ul>
      </td>
    </tr>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://blogfiles.pstatic.net/MjAxOTA1MDdfMiAg/MDAxNTU3MjE1NTU1MDQ3.UQAjrJHZPWjMr2KNYdX-t5jL3FUTUqQWPMiiMb0Bda4g.TRJ12_K-KlMZf_lcoKByKzY1jUeH-uR6TQC2OpjXrIgg.PNG.phh_92/%EC%A1%B0%EB%B3%84_Score_%EB%B9%84%EA%B5%90_%ED%99%94%EB%A9%B4.png?type=w2" width="350px"/>
    </td>
    <td>
      <ul>
        <li>조별 점수 확인 화면</li>
        <ol>
          <li>Quiz Game 이 끝나고 Score 에 마우스를 올려놓으면 각 팀별로 점수를 확인 할 수 있는 div 가 나타난다.</li>
        </ol>
      </ul>
    </td>
  </tr>
</table>
