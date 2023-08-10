# Canary-Deployment
![canary](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/445b7fac-c5e7-455c-9252-48bb6d7394e6)
![canary-linux](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/da2088ed-729c-457b-8c84-78c2cd46d2e0)


![canary-2](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/099223be-54a3-4cda-b76f-a197e2ae9533)

```bash 
 kubectl scale deploy blue-deployment --replicas=2 -n prod-ns
 kubectl scale deploy green-deployment  --replicas=2 -n prod-ns
```
![canraylinux2](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/b57a5421-f0c4-4fce-874c-4e07e242dee7)



![canary-3](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/365fd56b-2988-49dc-b6e2-4c5a0ff190b8)

```bash 
 kubectl scale deploy blue-deployment --replicas=1 -n prod-ns
 kubectl scale deploy green-deployment  --replicas=3 -n prod-ns
```
![canarlinux3](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/16191ed8-d73e-4e17-83cb-cbec4484c663)

![Screenshot 2023-08-10 214126](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/bc98626a-9a68-49f2-8089-8ebb6e8d748e)
![gr](https://github.com/chaithanya1812/Canary-Deployment/assets/111736742/630a28cc-914a-4b56-b2cc-381c0de754fd)
