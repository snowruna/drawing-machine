# 가디언 테일즈 추첨기

가디언 테일즈 내에서 상품 추첨을 하기 위한 프로그램 입니다.

## 기능
### 추첨
말 그대로 추첨 기능입니다.<br>
편의를 위해 일부 기능을 추가로 지원 합니다.<br>

* 추첨 이후에도 제외되지 않는 중복 추첨
* 한 상품에서 여러 명을 추첨하는 다중 추첨
* 유저 목록을 저장하고 불러오는 기능[^1]
* 조작 방지를 위한 실시간 현재시간 표시 기능

### 기록
추첨 결과를 실시간으로 기록합니다.

* 추첨 하는 순간 "최근 기록" 탭에서 추첨 시간과 함께 기록됩니다.
* 그 외 recent.log 파일에 추가로 기록됩니다.

### 검증
유저 목록에서 추첨을 매우 많이 반복해 확률을 검증하는 기능입니다.<br>
> 이 프로그램은 기본적으로 C# 기본 클래스인 Random 클래스를 이용합니다.<br>
> 난수 생성을 위한 시드는 기본적으로 시스템의 현재 시간을 이용해 난수를 생성합니다.<br>
> 대부분은 문제 없으나 문제가 있다고 판단될 경우 검증을 시도 해주세요.

## 요구사항
* Windows OS가 깔린 시스템
* .net framework 6.0 <br>
Windows 11 22H2에서 동작을 확인했습니다.

## 라이센스
프로그램의 소스코드는 MIT 라이센스로 배포됩니다.<br>
프로그램의 아이콘은 KONG STUDIOS, Inc.가 소유 하고 있습니다. [#](https://cafe.daum.net/GuardianTales/ARyY/695) [##](https://drive.google.com/drive/folders/1uVv14F9PyBq1MuznpFR3Bf8gfG-jE9dZ)

## 기타
C# 습작입니다. 어렵네요.


[^1]: 이 때 저장되는 파일은 .txt 파일이며 줄넘김으로 유저를 구분합니다.
