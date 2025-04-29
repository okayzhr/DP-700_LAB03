# DP-700_LAB03
# Delta Tables in Apache Spark - Microsoft Fabric Lakehouse

Dit project laat zien hoe je Delta Lake-tabellen maakt en gegevens verkent met behulp van Apache Spark in een Microsoft Fabric Lakehouse. Het maakt gebruik van Delta Lake om relationele semantiek toe te voegen voor zowel batch- als streaminggegevens. In dit project leer je hoe je Delta-tabellen kunt maken, gegevens kunt verkennen met SQL-query's en meer.

## Vereisten

Om deze oefening uit te voeren, heb je een Microsoft Fabric proefaccount nodig. Dit is vereist om een werkruimte en een lakehouse te maken.

### Stappen

1. **Maak een werkruimte aan**  
   Maak een werkruimte in Microsoft Fabric en zorg ervoor dat je het proefaccount hebt geconfigureerd.

2. **Maak een lakehouse en upload gegevens**  
   Maak een nieuw Lakehouse aan in de werkruimte en upload een CSV-bestand genaamd `products.csv` naar de folder `Files/products`.

3. **Verken de gegevens in een DataFrame**  
   Lees de gegevens in een DataFrame met behulp van een gedefinieerd schema en visualiseer de gegevens.

4. **Maak Delta-tabellen**  
   Gebruik Spark om de DataFrame op te slaan als een Delta-tabel. Er worden twee soorten tabellen aangemaakt:
   - **Beheerde Delta-tabel**: De gegevens worden beheerd door Microsoft Fabric.
   - **Externe Delta-tabel**: De gegevens worden extern opgeslagen, maar de metadata wordt beheerd door Fabric.

5. **Vergelijk beheerde en externe tabellen**  
   Verken de verschillen tussen beheerde en externe tabellen door SQL-commando’s te gebruiken om de eigenschappen van beide tabellen te bekijken.

6. **Gebruik SQL om een Delta-tabel te maken**  
   Maak een Delta-tabel met SQL en voer een `SELECT`-query uit om de gegevens te verkennen.

7. **Verken versiebeheer van Delta-tabellen**  
   Gebruik de transactiegeschiedenis van de Delta-tabel om versiebeheer toe te passen. Verander de prijs van bepaalde producten en verken de geschiedenis van de transacties.

8. **Analyseer Delta-tabellen met SQL-query's**  
   Maak een tijdelijke weergave van de gegevens en voer SQL-query’s uit om de gegevens per categorie te analyseren.

9. **Gebruik Delta-tabellen voor streaminggegevens**  
   Stel een streaminggegevensbron in, bijvoorbeeld een IoT-scenario, en sla de gegevens op in een Delta-tabel.

10. **Stop de stroom en maak de resources schoon**  
    Nadat je de streaminggegevens hebt geschreven naar de Delta-tabel, stop je de stroom en maak je de gebruikte resources schoon.

---

## Bestanden

- `products.csv` - Het bestand met productgegevens.
- **Delta-tabellen** - De tabellen die zijn gemaakt uit de gegevens in het Lakehouse.

---

## Licentie

Dit project is gelicentieerd onder de MIT-licentie - zie het [LICENSE-bestand](LICENSE) voor details.



![Schermafbeelding 2025-04-29 215750](https://github.com/user-attachments/assets/8cfe78e0-ffa5-4a6a-9347-e1a2c6975ab5)


![Schermafbeelding 2025-04-29 220742](https://github.com/user-attachments/assets/d3273dbd-3bae-42ee-89b1-e05edea636e8)


![Schermafbeelding 2025-04-29 230128](https://github.com/user-attachments/assets/e4dde7d8-38ab-4199-b216-82f16c4afed9)


![Schermafbeelding 2025-04-29 230956](https://github.com/user-attachments/assets/22d2163e-9a63-4f2d-aafc-56f9837973bb)


![Schermafbeelding 2025-04-29 231621](https://github.com/user-attachments/assets/5e4f6655-6ac0-4733-acc7-245bdded7a85)


![Schermafbeelding 2025-04-29 231931](https://github.com/user-attachments/assets/58b3a4b3-58ca-435f-baf8-cc4ba5c6f782)


![Schermafbeelding 2025-04-29 232121](https://github.com/user-attachments/assets/55b8b820-f535-4594-9925-9f3f178b680a)

![Schermafbeelding 2025-04-29 232426](https://github.com/user-attachments/assets/1a839fe6-9242-4943-b057-30a5b4a489c9)



![Schermafbeelding 2025-04-29 232519](https://github.com/user-attachments/assets/77e33a8c-326d-4d28-bd67-1f6cfb96f25c)



![Schermafbeelding 2025-04-29 232618](https://github.com/user-attachments/assets/6fa7be3a-04b8-4306-93cd-8094d37469a2)


![Schermafbeelding 2025-04-29 232729](https://github.com/user-attachments/assets/8cf3216d-ae7e-4ccd-bc5c-7702d88e4b24)



![Schermafbeelding 2025-04-29 232748](https://github.com/user-attachments/assets/9f6fa8a6-f2a9-4b9a-af95-2d5d74c55356)



![Schermafbeelding 2025-04-29 232915](https://github.com/user-attachments/assets/80909f64-7f98-459d-a440-144bb723a71c)




![Schermafbeelding 2025-04-29 233010](https://github.com/user-attachments/assets/d1ef3400-68ec-4f68-8ac5-a2610b0a34d7)


![Schermafbeelding 2025-04-29 233034](https://github.com/user-attachments/assets/57dfa0fc-53c1-496d-b563-7eb9a871e893)



![Schermafbeelding 2025-04-29 233050](https://github.com/user-attachments/assets/8228cb70-98c1-4753-b56f-e93d973cad13)

![Schermafbeelding 2025-04-29 233217](https://github.com/user-attachments/assets/74eb7702-3789-4f73-9740-2f1a9233210b)



![Schermafbeelding 2025-04-29 233322](https://github.com/user-attachments/assets/4da5ab75-6463-44cb-8244-7aa63b214845)



![Schermafbeelding 2025-04-29 233403](https://github.com/user-attachments/assets/d6a123d6-cdd7-4141-9b34-c5d81d064065)


![Schermafbeelding 2025-04-29 233442](https://github.com/user-attachments/assets/df53c673-117f-4cb9-98d3-5e0927411e5a)



![Schermafbeelding 2025-04-29 233552](https://github.com/user-attachments/assets/9894d069-6da6-4ad0-9fc5-68d71104912b)










