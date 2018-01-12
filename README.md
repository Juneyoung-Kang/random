# random - generate names by randomly picking from a word list
This repository contains shell script source code for random program which generate names by randomly picking from a word list.
You can type ```./random (int)``` to print (int) people or person. When you generate name(s), the generated word will have a ```#``` at the front and be a comment. Therefore, the word once printed will not be reprinted.
Also, because the comment is saved in the file, it will print the same result if the script is not deleted every time.

이 레포지토리는 문자 리스트로부터 랜덤으로 선정된 이름을 출력하는 Shell script로 작성된 소스코드를 담고 있습니다.
```"./random (정수)"```를 이용하여 ```(정수)```명의 이름을 wordlist로부터 출력합니다. 이미 선정된 이름 앞에는 ```#```이 붙게 되어 주석이 되므로 이름이 중복되어 출력될 일은 없습니다. 또한 이 주석은 아예 파일 자체에 저장되기 때문에 지우지 않는 이상 다시 Script를 실행하여도 같은 결과를 만들게 됩니다.

## How to install
```
$ git clone https://github.com/Juneyoung-Kang/random.git
```

## How to use
```
$ cd random
$ ./random //show help
$ ./random 4 //generate 4 people names by randomly picking from a word list
```
