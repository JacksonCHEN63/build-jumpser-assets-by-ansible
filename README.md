# build-jumpser-assets-by-ansible
利用ansible curl模組方式，自動化建立jumpserver資產

1.首先要到這邊 https://jumpserver.xxx.com/api/v1/assets/assets/ 去取得節點token

2.role 直接使用即可，default這邊要填寫相對應的變數

3.inventory 要選擇資產的節點，comment可填可不填

ref)

https://jumpserver.readthedocs.io/zh/1.4.8/user_api.html
