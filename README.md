# practice-analysis
>회귀, 분류, 시계열을 python과 R을 사용해 연습한 저장소
## 설정
* Python ver `3.10.10`
* 'numpy', 'pandas', 'matplotlib'는 필수적으로 설치
* 'inpynb'를 위해서 'jupyerlab'을 설치
* ctrl+shift+p 인터프리터 선택 --> venv python
```shell
(cmd)
$ python -m venv venv 
$ .\venv\Scripts\activate
$ (venv) pip install numpy pandas seaborn jupyterlab
$ pip freeze > requirments.txt
$ (venv) pip install -r requirments.txt
$ (venv) jupyter-lab <--jupyter-lab 실행
```
## ToDo
- [ ] 회귀문제([캘리포니아 집값데이터],http://lib.stat.cmu.edu/datasets)
- [ ] 분류문제([타이타닉 생존자 예측],https://www.kaggle.com/c/titanic)
- [ ] 시계열문제(문제 탐색중)

