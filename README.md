# ⚜ TEAM 1
![header](https://user-images.githubusercontent.com/87738954/130777709-153037c5-1944-4ce8-acc0-b4624842d482.png)
**팀 1 의 깃허브 계정입니다** 

# ⚜ 프로젝트 소개 
메모리 게임<br>
8x8 도트 매트릭스와 버튼을 이용한 간단한 게임입니다<br> 

# ⚜ 코드 소개 

```Python
# 랜덤값 입력하는 코드 

while True :
    userinput = [0,0,0,0,0,0,0,0,0,0]
    uersresult = [False,False,False,False,False,False,False,False,False,False]
    checkresult = 0
    temp = 0
    display.display_clear()
    display.char_m()
    
    while temp < 10 : 
    memorylist[temp] = urandom.randrange(1,5)
    
    while True : 
        if temp >= 1 and memortlist[temp] == memorylist[temp-1] : 
            memorylist[temp] = urandom.randrange(1,5)
        else :
            break
    temp += 1
```
```Python
# 사용자 입력 값이 틀렸을 경우

temp = 0 
while temp < index+1 :
    if userinput[temp] != memorylist[temp] : 
        checkresult = 1
    else : 
        userresult[temp] = True
    temp+=1
```
```Python
# 10회 다 성공했을 경우 

if index == 9 and checkresult !=1 :
    temp = 0
    while temp < 3 :
        display.display_clear()
        display.display_c1r1()
        utime.sleep(0,3)
        display.display_clear()
        display.display_c1r2()
        utime.sleep(0,3)
        display.display_clear()
        display.display_c2r1()
        utime.sleep(0,3)
        display.display_clear()
        display.display_c2r2()
        utime.sleep(0,3)
        temp += 1
    display.display_clear()
utime.sleep(2)
```

# ⚜ 회로도 
![회로도 그리기](https://user-images.githubusercontent.com/87738954/132500478-c727fc54-be23-4549-8386-4fa61bb15a04.png)
<br><br>

# ⚜ 프로젝트 기간
2021 07 21 ~ 2021 09 15

| 기간                | 설명                                                         |
| ------------------- | ------------------------------------------------------------ |
| 7.21(수)            | 프로젝트 시작                                                 |
| 8.11(수)            | 코드 기반 구성 및 발표자료 구성                                 |
| 8.18(수)            | 코드 완성 및 발표자료 마무리                                    |
| 8.25(수)            | 조립 완성                                                     |
| 9.01(수)            | 발표자료 완성 및 가발표                                        |
| 9.08(수)            | 발표 마지막 준비 및 깃허브 마무리                               |
| 9.15(수)            | 프로젝트 최종 발표 및 마무리                                    |


# ⚜ 참여인원

| [**김정민**🐌](https://github.com/minusminu) | [**홍수정💎**](https://github.com/SJHXjiah) | [**윤서연💌**](https://github.com/seoyeonnnnnnnnnn) |
| :----: | :----: | :----: |
| ![1](https://user-images.githubusercontent.com/87738954/131217389-121e1003-5771-442c-aec5-3a4ad2ebd146.png) | ![3](https://user-images.githubusercontent.com/87738954/131217412-ba8c2b4b-faad-42ed-8ff6-0dc07b8077a1.png) | ![4](https://user-images.githubusercontent.com/87738954/131217401-adaa4383-d687-4718-ae2e-d29d65e51ecf.png) |
| 디자인/총무 | 디자인/발표 | 코딩/발표 |
