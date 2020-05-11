# CRUD Project #
------------
## Project 소개 ##

> 음식 배달 업체 관리 프로그램
> : 등록 된 음식점의 전체 목록은 물론이고, 카테고리나 배달 시간에 따라 검색해 소비자의 needs에 맞는 음식점을 빠르게 찾을 수 있습니다.
> 이 외에도 관리를 위한 여러가지 기능을 포함하였습니다.

## 기능 설명 ##

> 1. Create : 신규 음식점의 정보를 목록에 추가합니다.
>> 음식점 이름 / 전화번호 / 카테고리 / 배달시간(빠름, 느림, 보통) 을 입력하여 정보를 생성합니다.
>> 음식점 이름이 중복될 시, create할 수 없습니다.
> 2. Read : 목록에 있는 모든 음식점의 정보를 출력합니다.
> 3. Update : 목록에 있는 음식점 중 원하는 음식점의 정보를 수정합니다.
>> 음식점의 전화번호 / 카테고리 / 배달시간(빠름, 느림, 보통)을 수정합니다.(이름 수정X)
> 4. Delete : 목록에 있는 음식점 중 원하는 음식점의 정보를 삭제합니다.
> 5. Search(name) : 원하는 음식점의 정보를 찾아 출력합니다.
> 6. Search(time) : 원하는 배달시간의 음식점을 모두 찾아 그 정보를 출력합니다.
> 7. Seqrch(ctgr) : 원하는 카테고리의 음식점을 모두 찾아 그 정보를 출력합니다.
> 8. Delete(condition) : 원하는 조건의 음식점을 모두 삭제합니다.(time or ctgr에 따라 삭제)
> 9. Delete(all) : 목록 내의 모든 음식점의 정보를 삭제합니다.
> 10. Load : .txt file 내 모든 음식점의 정보를 읽어와 목록에 추가합니다.
> 11. Save : 프로그램 내의 모든 음식점 정보를 .txt file에 저장합니다.
> 0. Quit : 프로그램을 종료합니다.

## Make Utility ##

Program Build and Run
```
$ make main
$ ./main
```

Program Build(with DEBUG) and Run
```
$ make main_debug
$ ./main
```

Build Reset
```
$ make clean
```

