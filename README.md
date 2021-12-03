# 문제 1
vimgolf put 5f0f5fbe280fbf000c233304

* #### 나의 점수 : 8 점
* #### 나의 정답
  * GWi"< END >< C-@ >ZZ
* #### 해설
  
  대문자 G는 파일의 마지막 행의 맨 앞으로 이동
  
  대문자 W는 문자 단위로 앞으로 이동한다. (특수문자 신경x)
  
  소문자 i는 현재 커서 위치에서 입력 모드를 시작한다.
  
  "는 그냥 입력모드에서 "
  
  END는 현재 라인 끝으로 이동한다.
  
  C-@(ctrl+@)는 앞에서 입력한 것들을 그대로 입력한 후 일반모드로 다시 돌아간다.
  
  대문자 ZZ는 변경사항 저장 후 종료이다.
  
* #### 풀이과정
  ![image](https://user-images.githubusercontent.com/93646339/144608932-5b946d81-3214-45ee-93c9-b263e01ac139.gif)
  
# 문제 2 
vimgolf put 603ba26a01b4d00009c10a49

* #### 나의 점수 : 19 점
* #### 나의 정답
  * w*:s//vim/g<CR>)B*g&ZZ
* #### 해설
  
  소문자 w는 다음 단어의 앞으로 이동한다.(특수문자도 하나의 단어로 침 ABC: A앞에 커서가 있고 w를 누르면 : 앞으로 커서가 이동)
 
  *는 커서 앞에 있는 단어를 선택한다. (특수문자 무시)
 
  :s/(원래 문자열)/(변경 문자열)/g는 현재 행에 있는 모든 문자열을 바꾼다.
 
  위에서는 이미 *로 단어를 선택해서 공백으로 씀
 
  CR(ENTER)은 입력모드에서 일반모드로 돌아옴
   
  )는 다음 문장의 처음으로 커서를 이동한다.
   
  대문자 B는 문자 단위로 뒤로 이동한다. (특수문자 신경x)
   
  *는 커서 앞에 있는 단어를 선택한다. (특수문자 무시)
   
  &는 방금 실행했던 :s를 그대로 반복한다. 그런데 앞에 g가 붙었으므로 전체 적용 
   
  대문자 ZZ는 변경사항 저장 후 종료이다.

* #### 풀이과정
  ![images](https://user-images.githubusercontent.com/93646339/144612492-a03ee0e7-e27c-4de5-b6bb-010324c79cba.gif)

# 문제 3
vimgolf put 5f1063aa8361810006e73210

* #### 나의 점수 : 20 점
* #### 나의 정답
  * Gqq-O// < C-N > TODO < ESC >q@qZZ
* #### 해설
   
   대문자 G는 파일의 마지막 행의 맨 앞으로 이동
   
   qq(기록하고 싶은 것)q 는 qq를 친 다음 모든 것들을 기록 해두고 마지막에 q를 쓰면 그 기록이 저장 된다
   
   그리고 그 기록을 사용하고 싶을 때 @q 를 치면 그 기록이 사용되어 진다. 
   
   @앞에 숫자를 붙이면 그 숫자만큼 반복해서 실행된다. 아무것도 안쓰면 1이 생략되어 들어감.
   
   -는 위의 행으로 이동하고 그 행의 맨 앞 단어 앞으로 커서를 이동한다.
   
   대문자 O는 현재 커서가 위치한 자리위에 행하나를 만들고 그 행에서 입력모드를 시작한다.
   
   //는 그냥 입력모드에서 입력한 것
  
   C-N(ctrl + N)는 커서 바로 다음 단어를 자동완성시켜주는 기능이다. 
   디폴트는 다음 단어이고 방향기를 이용하여서 원하는 단어를 선택할 수 도있다. 물론   그 파일안에 있는 단어만 자동 완성이 가능하다.
   
   TODO도 그냥 입력모드에서 입력한 것
   
   ESC는 입력모드에서 일반모드로 나온다.
    
   q는 기록종료
    
   @q 지금까지 기록한 것을 1번 반복
    
   대문자 ZZ는 변경사항 저장 후 종료이다.
   
   
   
   
* #### 풀이과정
  ![images](https://user-images.githubusercontent.com/93646339/144616269-bec9dcdf-96bb-4882-8841-f8491c07edef.gif)

# 문제 4
vimgolf put 9v0060da5177000000000209

* #### 나의 점수 :  점
* #### 나의 정답
  * 
* #### 해설

* #### 풀이과정


# 문제 5
vimgolf put 6013804df3308e0009368f1c

* #### 나의 점수 :  점
* #### 나의 정답
  * 
* #### 해설

* #### 풀이과정
