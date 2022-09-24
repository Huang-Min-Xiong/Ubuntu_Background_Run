#### Ubuntu背景執行:
- python3 test.py & 

查看行程資訊(指令: ps):
- Ex: 19145 pts/0 00:00:00 python3 test.py

中止程式:
- kill 19145(PID)

注意事項:
若是使用ssh連線方式，關閉視窗後該程式就會終止，
可以透過nohup方式，就不會造成此問題!
- ex: nohup python3 test.py &
 
