
# 1. 해야할 것

1. 게임산업 뉴스 읽기 
2. 개인 공부  
3. 니어 오토마타 스펙 측정

[유튜브: For each Loop](https://www.youtube.com/watch?v=TCDlqJHEGXI)



# 2. 오늘 배운 것

<details>
<summary>접기/펼치기</summary>

## 니어 오토마타 스펙 측정
![길이](https://github.com/user-attachments/assets/da5ba862-0183-4748-bcad-f10c89f78fd9)

10m 달리기 측정



</details>




# 3. 개선
![image](https://github.com/user-attachments/assets/e9493ca1-af00-47d6-8eeb-c64bb4db0895)


<details>
<summary>접기/펼치기</summary>

### 틱이벤트를 통한 문 열기 방식 확인
  
![image](https://github.com/user-attachments/assets/0df2d40f-3dd9-485d-842d-ce15ad8b6a4d)

![image](https://github.com/user-attachments/assets/e84ce29b-271a-45b4-9a1f-b51212a198e1)

![image](https://github.com/user-attachments/assets/7db103df-9fb5-4fab-af45-8fb67c193fe2)

### 틱이벤트를 사용하지 않기 위해 개선
![image](https://github.com/user-attachments/assets/47d9c400-0337-45d4-8cdb-a4293ef8185d)
```
reverse for each loop를 사용했다.
그냥 for each loop를 사용하면 index를 지웠을때 아래에 있던 index 값이 한칸 올라와서
index를 두 개 지워야하는데 하나만 지우는 현상이 발생했기 때문이다.

reverse fore each loop를 사용하면 아래에서부터 삭제하면서 위로 올라가기 때문에
index 두개가 지워져도 index 값이 하나 올라가서 살아나는 불상사가 생기지 않는다.
```


</details>



# 4. 생각


