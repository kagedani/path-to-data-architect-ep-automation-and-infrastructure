# 🏗️ Progettazione Infrastruttura e Automazione (CI/CD)

## 📖 Contesto
All’avvio del progetto non esistono strumenti di **code repository** né automazioni CI/CD.  
Le risorse vengono create direttamente tramite console e gli sviluppatori di **quattro fornitori diversi** hanno pieno accesso a qualsiasi servizio AWS.  

Il codice risiede nei job, script o nei repository di un fornitore storico. Sono state definite **linee guida** per la nomenclatura delle risorse e per l’uso corretto dei principali servizi dello stack AWS:  

- AWS S3  
- AWS Athena  
- AWS Redshift  
- AWS Glue  
- AWS AppFlow  
- AWS Lambda  

> Il cliente non possiede competenze specifiche in ambito dati: **nessun concetto di data product** né di ownership del dato.

---

## 🎯 Obiettivi del progetto
- Implementare un framework di **CI/CD** su entrambi gli account (Test / Prod)  
- Minimizzare i costi, sia progettuali sia operativi  
- Creare una soluzione compatibile con tutti i servizi AWS utilizzati dal cliente  

---

## ⚠️ Requisiti e vincoli
- Deadline definita: **circa 4 mesi**  
- Progetto **chiavi in mano**  
- Utilizzo esclusivo di tecnologie **AWS**

---

## 🛠️ Stack Tecnologico
Il progetto utilizza principalmente i servizi AWS già in uso dal cliente, integrati in un flusso automatizzato per CI/CD e gestione infrastruttura.

<img src="./images/aws-s3-icon.png" width="26" alt="AWS S3" /> **AWS S3**  
<img src="./images/aws-athena-icon.png" width="26" alt="AWS Athena" /> **AWS Athena**  
<img src="./images/aws-redshift-icon.png" width="26" alt="AWS Redshift" /> **AWS Redshift**  
<img src="./images/aws-glue-icon.png" width="26" alt="AWS Glue" /> **AWS Glue**  
<img src="./images/aws-appflow-icon.png" width="26" alt="AWS AppFlow" /> **AWS AppFlow**  
<img src="./images/aws-lambda-icon.png" width="26" alt="AWS Lambda" /> **AWS Lambda**  
<img src="./images/aws-cloudformation-icon.png" width="26" alt="AWS Cloud Formation" /> **AWS Cloud Formation**  
<img src="./images/aws-codecommit-icon.png" width="26" alt="AWS Code Commit" /> **AWS Code Commit**  
<img src="./images/aws-codebuild-icon.png" width="26" alt="AWS Code Build" /> **AWS Code Build**  
<img src="./images/aws-codepipeline-icon.png" width="26" alt="AWS Code Pipeline" /> **AWS Code Pipeline**  

---


## 👨‍🏫 Tutor
- [Daniele Uboldi](https://github.com/kagedani)
