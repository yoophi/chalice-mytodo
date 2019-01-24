# chalice-mytodo

<https://github.com/aws-samples/chalice-workshop> 의 코드를 python3 환경에 맞춰 일부 수정 

아마존의 문서 참고: <https://chalice-workshop.readthedocs.io/en/latest/todo-app/index.html>

```
pip install -r requirements.txt
python createtable.py --table-type app
python createtable.py -t users
```

사용자 추가

```
python users.py -c
```

테스트 및 배포

```
chalice local
chalice deploy
```
