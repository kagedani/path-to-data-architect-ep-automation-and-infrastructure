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

---


## 👨‍🏫 Tutor
- [Daniele Uboldi](https://github.com/kagedani)
