# dev-error-log






# Error: listen EACCES: permission denied 0.0.0.0:3000







  
  net stop winnat
  
  
  ![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/605ae7bb-e5f0-45df-996b-6243967bc653)
  
  
  
  
  
  
  
  net start winnat
  
  
  
  
  
  ![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/12b5ea22-ee39-4279-a92d-bb1e7f5656ae)
  
  
  
# 액세스 차단됨: 이 앱의 요청이 잘못되었습니다  
  
  ![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/1116ad97-fb2c-481e-9eed-fb287bca1cb1)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/1709a084-fdef-49c6-9701-0021b0c4f6a6)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/e60cd4a7-0b68-4687-b4f0-02fdbd66a0cd)





http://localhost:3000/api/auth/callback/google


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/1ceec33e-aef0-430f-a7ba-166d83608d09)


npm install next-auth
or
yarn add next-auth








![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/c4f84864-10e9-4ce6-b7dd-2571794e8e7f)









![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/10f7ce48-3e14-425d-ad70-bbff1e09b1e7)




root@ns1:/home/sangbinlee9/front-end/mini-do# lsof -i tcp:3000
COMMAND     PID USER   FD   TYPE DEVICE SIZE/OFF NODE NAME
next-serv 19209 root   22u  IPv6  77991      0t0  TCP *:3000 (LISTEN)
root@ns1:/home/sangbinlee9/front-end/mini-do# kill -9 19209
root@ns1:/home/sangbinlee9/front-end/mini-do# lsof -i tcp:3000
root@ns1:/home/sangbinlee9/front-end/mini-do#

