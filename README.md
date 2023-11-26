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






![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/6f68f16a-4971-4f8b-a214-0f1f5c5d7b00)

![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/a5889f51-36a9-4d1d-a1f6-b5b53315223f)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/28be298a-7594-435a-a0b8-30631b0f5266)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/760557cc-8f97-4580-8120-1e38f1961a1f)






![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/f5c70522-f686-4bc4-96f9-44ad403ac6e3)






![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/b80bb64c-6b04-4762-a63a-75488da75abb)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/ca83eb44-c999-41b8-bb25-6554f1dc0f64)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/35149fdb-6a66-49cf-9330-cf5fcd019cbc)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/895928b7-0a2e-4dfb-9080-d76b2d4e0888)










# 구글 oauth2 - 로컬 ok


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/f149440b-4dc7-4bbd-94dc-a63fdfb067eb)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/b9338a80-3689-4e80-a135-9cf56b081828)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/b5fc4013-613b-4385-b6f4-259d9986a75b)









# 구글 oauth2 - production ok?


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/8485f2fb-b200-44de-834a-3627a7c64eed)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/705f5723-0ddb-43cd-bd2e-4573f23aa433)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/0bdbc9fa-fe14-499f-a5f4-a9e69bc540e9)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/6343ffd4-7b46-434b-80c5-976bfa04442b)




![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/2ce1f9a3-0e81-4941-a5f8-cfcc409c13c5)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/4563fedd-c471-491e-ae1f-9f7f293902c7)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/76e176fa-62af-45dd-b26b-11f3f2817d90)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/ebced283-f341-4946-803d-163eb41a5e2c)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/18284a3f-c657-4f53-bf8b-7ad00fadee2e)

![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/8395c0f2-c5aa-4856-93a5-82476fd812f4)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/7f64ce14-2ed9-471f-8005-1b692d9a8728)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/b40793ea-41df-4aed-b516-0787f05520a0)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/d84f8867-92c0-4326-9380-48d1947dcdc7)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/c857e025-47f3-474b-998d-08eb3fb801c8)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/2310c603-a54d-404c-a9a5-3ffa441cba8d)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/179d4f17-d7b0-4bb2-a344-b98d79f0204a)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/25deecf4-ed8d-417b-a61d-5bbb966043ab)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/71d6a836-a05b-4713-b1c6-925d0576ffdf)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/c240a55c-a07a-4426-bde0-f2b6a1f97658)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/1a2e37bc-6d7b-4019-8dc0-1910e37e9d0a)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/ce288d81-f2ae-49ae-95c7-b2b008a9c88e)



![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/bb7507f4-e10c-4e4e-b0bc-4500d43f4a3d)

![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/954e46be-1510-4756-882b-b0fb495b331f)

![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/1a71b9d6-e09e-46ec-bde7-0b1f4e3df4f1)


![image](https://github.com/sangbinlee/dev-error-log/assets/4024414/8e7ea8bf-fdb9-4322-b6b4-603ff7cee004)

