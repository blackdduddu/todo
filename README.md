# todo
init commit

## todo 기능
- 등록
- 수정
- 삭제

- form
- list
- list-item
- 데이터 형식
```
todo = [
            {
                id: number,
                title : 'string',
                done : boolean,
            },
            {
                id: number,
                title : 'string',
                done : boolean,
            },
        ]
```
    

- 데이터 저장 : 로컬스토리지 
## 폴더구조
```
    component
        ㄴ form.jsx
            - 사용자 인풋 받음
            - 입력 받은 값 확인
            - 에러처리
            - 벨리데이션 체크 ()
            - submit event
        ㄴ todo
            ㄴ list.jsx
            ㄴ item.jsx
            ㄴ index.jsx
        ㄴ comment
            ㄴ list.jsx
            ㄴ item.jsx
            ㄴ index.jsx
```