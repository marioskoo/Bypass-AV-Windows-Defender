# Bypass-AV-Windows-Defender

Questa è una semplice guida creata da Mariano Forte per scopi di ricerca, l'obiettivo è quello di utilizzare Chimera per offuscare il payload creato precedentemente con Hoaxshell. Bypassando così qualunque AV o qualsiasi Defender.





1) Come primo step andiamo ad utilizzare Hoaxshell un tool che ci permette di creare dei payload personalizzabili e che nel nostro caso funge anche da server di C2 per poter controllare la nostra vittima.
![](chimera1.png)

<img width="773" alt="chimera1" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/f14cc5d0-a630-431f-9b00-2c657503bd18">

Quindi questo sarà il nostro payload personalizzato creato in precedenza con Hoaxshell.

<img width="779" alt="Screenshot 2023-12-29 alle 15 02 34" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/e1615f82-d982-41d1-ac78-813dbbbf527e">


2) Successivamente come secondo step andremo ad utilizzare Chimer per offuscare il nostro pyaload in powershell creato precendetemente.

<img width="783" alt="Screenshot 2023-12-29 alle 15 04 27" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/a3628f54-72d6-4a03-a67c-e6954fd875e1">

Al lancio di questo comando Chimera inizierà ad offuscare il codice powershell da come possiamo vedere.

<img width="781" alt="Screenshot 2023-12-29 alle 15 06 00" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/834a0baa-3a63-4ab8-8c44-8560265e66b7">
<img width="781" alt="Screenshot 2023-12-29 alle 15 06 14" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/98ce7564-61cc-402f-8f44-ef96037975b9">

al termine questo sarà il nostro payload offuscato.

<img width="781" alt="Screenshot 2023-12-29 alle 15 06 38" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/19fadf3c-e0d9-4e69-ae12-89aa1740c578">

3) Come ultimo step andiamo a scaricare il payload sulla macchina vittima (ovviamente in maniera semplificata scaricando direttamente il payload).


   <img width="554" alt="Screenshot 2023-12-29 alle 15 13 19" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/4ebe0d4d-fc7c-4d14-8124-6def05a79587">

   Una volta scaricato ed eseguito il payload noteremo un callback sul nostro Hoaxshell, nel quale noteremo che abbiamo ottenuto l'accesso tramite una reverse shell alla nostra macchina vittima.

   <img width="553" alt="Screenshot 2023-12-29 alle 15 15 31" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/ab63b951-2d18-4462-a30a-85b8b83830a1">

   Adesso che abbiamo ottenuto una shell possiamo eseguire i comandi che più preferiamo.


<img width="553" alt="Screenshot 2023-12-29 alle 15 16 14" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/733033ad-0f6b-4f7f-8280-255c2cabd108">

   

