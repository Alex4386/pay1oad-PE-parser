# PE-parser
![image](https://user-images.githubusercontent.com/27724108/62987479-f78cd400-be7a-11e9-8ffa-9b19fe84b571.png)

![pe-parser builder](https://github.com/Alex4386/pe-parser/workflows/pe-parser%20builder/badge.svg)

## Table of Contents
* [한국어](#한국어)
* [English](#English)

## 한국어

### 이게 뭐죠?
가천대학교 정보보안 동아리 Pay1oad의 디지털 포렌식 과제 - 파싱 프로그램을 만들어라의 결과물 레포입니다.  

### 왜 굳이 크로스플랫폼으로??
PE File은 Windows에서 많이 쓰고, 대부분 PE 파일용 역공학용 프로그램 자체도 윈도우용으로 많이 만들어져 있습니다. 하지만 저는 MacBook Pro를 쓰고 macOS를 주 운영체제로 쓰죠.   
문제는 **이거 하나 때문에 Parallels 켜기는 너무 귀찮거든요!** 마침 과제도 이걸로 받았겠다 그냥 PE File Parsing 프로그램 만들어 버렸습니다.  
게다가 DOS 프로그램 분석하는건 정말 헬이었던 관계로, 그냥 MZ도 Parsing 가능하게 작업했습니다.  

### 컴파일 방법
#### Linux, macOS
1. gcc와 g++, make를 설치 합니다.
2. 레포 폴더 안에 있는 `make` 를 실행합니다.
3. 새로 생긴 `./build/pe-parser` 파일을 실행합니다.

#### Windows
1. 레포 폴더 안에 있는 솔루션 파일을 실행합니다.
2. 평상시 진행하던 방법대로 컴파일 합니다.

### Special Thanks
* 2019 Pay1oad Reverse Engineering Team
* 2019 Pay1oad Digital Forensics Team
and...

* ZUN (동프 때문에 리버싱 시작한것도 있어요.)

## English
### What is this?
This Repository is an assignment of Pay1oad(The InfoSec Club of Gachon Univ.) 's study: Digital Forensics.  

### Why did you made it cross-platform
PE File Structure is usually used in Windows Systems, So Lots of Reverse Engineering Programs for PE Files are built only for Windows. But I use macOS as main operating system. And I am too lazy to turn the Parallels on because of just that, So.....
I decided to make it, since i got an assignment about it!  
Now Supports parsing MZ Headers either!  

### How to Compile
#### Linux, macOS
1. install gcc and g++ and make.
2. run `make` inside of the repository
3. execute newly created `./build/pe-parser` executable.

#### Windows
1. Open the solution file inside of the repository.
2. Compile as you do on other Visual Studio Projects.

### Special Thanks
* 2019 Pay1oad Reverse Engineering Team
* 2019 Pay1oad Digital Forensics Team
and...

* ZUN (Creator of the TouHou Project (*who literally hooked me into Reverse Engineering*))

This Repository comes with **Fantasy Seal™ Technology**.
