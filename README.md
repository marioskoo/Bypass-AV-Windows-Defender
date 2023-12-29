# Bypass-AV-Windows-Defender

Questa è una semplice guida creata da Mariano Forte per scopi di ricerca, l'obiettivo è quello di utilizzare Chimera per offuscare il payload creato precedentemente con Hoaxshell. Bypassando così qualunque AV o qualsiasi Defender.





1) Come primo step andiamo ad utilizzare Hoaxshell un tool che ci permette di creare dei payload personalizzabili e che nel nostro caso funge anche da server di C2 per poter controllare la nostra vittima.
![](chimera1.png)

<img width="773" alt="chimera1" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/f14cc5d0-a630-431f-9b00-2c657503bd18">

Quindi questo sarà il nostro payload personalizzato creato in precedenza con Hoaxshell.

<img width="779" alt="Screenshot 2023-12-29 alle 15 02 34" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/e1615f82-d982-41d1-ac78-813dbbbf527e">

2)Successivamente come secondo step andremo ad utilizzare Chimer per offuscare il nostro pyaload in powershell creato precendetemente.

<img width="783" alt="Screenshot 2023-12-29 alle 15 04 27" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/a3628f54-72d6-4a03-a67c-e6954fd875e1">

Al lancio di questo comando Chimera inizierà ad offuscare il codice powershell da come possiamo vedere.

<img width="781" alt="Screenshot 2023-12-29 alle 15 06 00" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/834a0baa-3a63-4ab8-8c44-8560265e66b7">
<img width="781" alt="Screenshot 2023-12-29 alle 15 06 14" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/98ce7564-61cc-402f-8f44-ef96037975b9">

alla fine del processo di offuscamente eseguito dal tool avremo il nostro payload offuscato.

<img width="781" alt="Screenshot 2023-12-29 alle 15 06 38" src="https://github.com/marioskoo/Bypass-AV-Windows-Defender/assets/105681127/19fadf3c-e0d9-4e69-ae12-89aa1740c578">


