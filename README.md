# xv_angie
Pagina de Invitacion de xv de angie

primero instala el CLI de google cloud ejecutando esto en powershell

(New-Object Net.WebClient).DownloadFile("https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe", "$env:Temp\GoogleCloudSDKInstaller.exe") & $env:Temp\GoogleCloudSDKInstaller.exe

accede a gcloud con tus credenciales
gcloud auth login

![image](https://github.com/user-attachments/assets/5f3544fb-fc97-43f0-ad72-e79e5b9383f9)

accede a tu projecto

gcloud config set project fiestaxvangie
![image](https://github.com/user-attachments/assets/8977434f-1af0-4120-a782-5eae43d6a567)

deployaa el proyecto creado

gcloud app deploy 
![image](https://github.com/user-attachments/assets/ad49f88f-8a79-4c25-ae5a-1e4ab7d5eb92)

selecciona Y
espera que se deployee el proyecto.
![image](https://github.com/user-attachments/assets/4acaaba0-c39d-49c2-9fba-03d9e871a0e2)

cuando ya este el proyecto arriba veras algo como esto:
![image](https://github.com/user-attachments/assets/f2d11001-38e0-4159-92df-693de77ec633)

accede a tu web app con el siguiente comando:
gcloud app browse


despues configura todos los accesos de google.
extrae la api key
