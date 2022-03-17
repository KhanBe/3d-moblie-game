# 3d-moblie-game
This project is 3D moblie game


### 3D 쿼터뷰 모바일 게임

<details>
  <summary>일지</summary>
  
#### 2022-03-10   
- 캐릭터 구현
- 캐릭터 움직임   

#### 2022-03-11   
- 맵
- 카메라 구도
- 캡슐 콜라이더 적용 후 경사진 곳을 가면 캐릭터가 계속 구르게 됨 (오류)   

#### 2022-03-13   
- 경사진 곳을 가면 캐릭터가 계쏙 구르는 오류
- 원인 : 외부 충돌에 의해 **회전속력**이 발생
- 해결 : FixedUpdate에 회전속력 값을 zero로 만들어준다.
```rb.angularVelocity = Vector3.zero;```

- 다시 박스콜라이더로 교체   

#### 2022-03-16
- UI panel 연습, 
  
  </details>
