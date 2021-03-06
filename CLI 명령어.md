# CLI 명령어

Unix 명령어를 학습합니다.



## Summary

| 명령어                                                       | 사용 예시                             | 설명        |
| ------------------------------------------------------------ | ------------------------------------- | ----------- |
| `ctrl + c`                                                   | '를 닫지 않았을 때                    | 취소        |
| `CTRL+L`                                                     | 깔끔하게 정리하고 싶을 때             | 터미널 청소 |
| `CTRL+W`                                                     | 전체가 아닌 한단어만 삭제하고 싶을 때 | 단어 삭제   |
| `ctrl+d`                                                     | 종료하고 싶을 때                      | 터미널 종료 |
| `s mkdir <dir_name>`                                         | 폴더 생성할때                         | 폴더 생성   |
| $ cd <dir_name>                                              | 이동할떄                              | 폴더 이동   |
| `$ mkdir`                                                    | $ mkdir <dirname>                     | 폴더생성    |
| 안전삭제<br />`$rm -r <dir_name>`<br/><br/>#강제삭제<br />`$rm -rf <dir_name>` | 폴더 삭제                             | 폴더삭제    |
| `$ touch <filename>`                                         | 파일 생성                             | 파일 생성   |
| `$ rm <filename>`                                            | 파일 삭제                             | 파일 삭제   |
| `$ start <filename>`                                         | 파일 실행                             | 파일 실행   |
|                                                              |                                       |             |

## 단축키 명령어

- 취소 =>`CTRL+C`

- 터미널 청소 => `CTRL+L`

- 단어 삭제 => `CTRL+W`

- 터미널 종료 => `CTRL+D`

- 상하 방향키 => 이전/다음 명령어 불러오기

- 좌우 방향키 => 커서 이동

  

## 프롬포트(pompt$)

터미널의 `$`마크는, 명령어 입력 준비 완료를 의미

즉, `$`마크가 없을 경우에는, 명령어를 입력해도 제대로 동작하지 않습니다.



## 폴더

폴더는 단순히 파일/폴더를 묶어줍니다.



### 폴더 생성하기

 ```
S mkdir <dir_name>
 ```



### 폴더 이동하기

```
$cd <dir_name>
```





### 폴더 삭제하기

```
# 안전삭제
$rm -r <dir_name>

#강제삭제
$rm -rf <dir_name>
```



# 파일



### 파일 생성하기

```
$ touch <filename> #확장자까지 반드시 작성
```





### 파일 삭제하기

```
$ rm <filename>
```



### 파일 실행하기(컴퓨터 기본 실행 프로그램)

```
# windows
$ start <filename>

#macOS + linux
$ open <filenmae>
```



### 복사/이동

```
$ cp <original_name> <copy_name>
```



### 이동

```
# 이름 바꾸기
$ mv <original_name> <another_name>

#이동하기
$ mv <original_name> <another_path>
```



## Vim 편집기



