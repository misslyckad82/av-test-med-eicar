<<<<<<< HEAD
Detta Python-script används för att kontrollera vilket operativsystem som scriptet körs på.

Om scriptet körs på en Windows-klient skrivs dessutom en EICAR-testfil, innehållandes EICAR-signaturen, för malware-detektion.
Detta ska trigga Windows-klientens antivirusprogram att sätta den skrivna filen i karantän, alternativt ta bort filen.
=======
Detta script används för att detektera vilket operativsystem en klient använder. 
Om scriptet körs på en Windows-klient skrivs dessutom en fil innehållandes EICAR-signaturen.
Detta ska trigga Windows-klientens antivirusprogram att sätta den skrivna filen i karantän.
>>>>>>> 387ae6599850336b90385ac61b34d287fe809da2
 
För att testa scriptet i Kali Linux-terminalen skrivs <python3 av-test-med-eicar.py>.
