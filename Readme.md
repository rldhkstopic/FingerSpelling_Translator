# 데이터 수집 방법

1. 디바이스에 사용 가능한 캠을 준비
2. 장치관리자에서 캠 번호를 확인하고 코드 수정
4. 캠 위에 Overlap되는 Hand Landmark Recognition에 대해 한 손만 인식되도록 한다.
5. 한 손은 수집하려는 데이터에 대한 수어 동작을 한다.
6. Landmark가 잘 표시되어있는지 확인하고, 잘 되어있다면 `Enter`를 눌러서 저장
    - 저장되는 데이터는 `현재 프레임 이미지`와 `Hand Landmark의 각 Joint에 대한 (x, y, z)좌표`입니다.


video가 떠있는 상태에서 조작 키
'q' : window destroy
'c' : 수집할 문자 index를 increase (next char)
'Enter' : 현재 이미지 프레임 + mediapipe 좌표 저장
    - 만약, 손이 인식되지 않으면 enter를 눌러도 반응없음
    
- 각 자음, 모음에 대해 최소 50개 이상 수집
- 그 외 질문사항은 카톡으로 주세요
