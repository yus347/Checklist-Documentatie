# 📱 Samsung XCover 7 – Checklist & Documentatie 
**Amsta Zorg**

Deze checklist wordt gebruikt bij het **inspoelen van Samsung XCover 7**.
✅ Voltooi eerst deze checklist, daarna kun je verder met de configuratiehandleiding.

---

## 1. App Installatie – Controle

Controleer of de volgende apps geïnstalleerd zijn:

- [ ] CLB Messenger  
- [ ] DAVx5  
- [ ] Linphone CLB  
- [ ] SureMDM Agent  
- [ ] Kadex Notifier  
- [ ] Google Meet 
- [ ] Zijknoppen starten CLB  

➡ **Geen enkele app mag ontbreken**

---

## 2. App Instellingen – Controle (Voor elke app)

### 2.1 Meldingen

**Pad:** `Instellingen → Apps → [Appnaam] → Meldingen`

- [ ] Meldingen → **Toegestaan**  
- [ ] Geluid → **AAN**  
- [ ] Trilling → **AAN**  
- [ ] Pop-ups → **Toegestaan**  
- [ ] Vergrendelscherm → **Zichtbaar**  

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/21.png)

---

### 2.2 App-rechten (machtigingen)

**Pad:** `Instellingen → Apps → [Appnaam] → Machtigingen`

- [ ] Camera → **Toegestaan**  
- [ ] Locatie → **Toegestaan**  
- [ ] Telefoon → **Toegestaan**  
- [ ] Nabije apparaten → **Toegestaan**  
- [ ] Bestanden/Media → **Toegestaan**  
- [ ] Meldingen → **Toegestaan**  

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/20.png)

---

### 2.3 Batterij

**Pad:** `Instellingen → Apps → [Appnaam] → Batterij`

- [ ] Batterijgebruik → **Onbeperkt**  

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/19.png)

---

## 3. Zijknoppen Instellen (Samsung XCover 7) alleen voor CLB Messenger

1. Ga naar **Instellingen**.
2. Open **Geavanceerde functies**.
3. Ga naar **Zijknop**.
   
---

### Instellingen:
- **Twee keer drukken → CLB Messenger**
- **Lang indrukken → Menu uitschakelen**

4. Ga één stap terug.
5. Ga naar **Knop XCover**.
6. **Koppel deze aan CLB Messenger**.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/7.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/8.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/9.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/10.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/11.png)

---

## 4. Niet Storen (DND) Instellen voor CLB

1. Ga naar **Instellingen**.
2. Open **Apps**.
3. Tik rechtsboven op **⋮ (3 puntjes)**.
4. Kies **Speciale app-machtigingen**.
5. Ga naar **Niet storen (DND)**.
6. Zoek **CLB Messenger** en zet deze op **Toegestaan**.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/6.png)

---



## 5. Gemini Uitschakelen

1. Ga naar **Instellingen**.
2. Zoek naar **Gemini**.
3. Zet **Gemini UIT**.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/12.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/13.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/14.png)

---

## 6. Netwerk & Functionaliteit

---

- [ ] <span title="Verbind het toestel met een stabiel WiFi-netwerk">WiFi verbonden</span>  
- [ ] <span title="Controleer of mobiele data actief is (4G icoon zichtbaar)">4G actief</span>  
- [ ] <span title="Test CLB Messenger terwijl WiFi is ingeschakeld">CLB getest via WiFi</span>  
- [ ] <span title="Schakel WiFi uit en test CLB via mobiele data">CLB getest via 4G</span>  
- [ ] <span title="Doorloop alle CLB instellingen zoals beschreven in stap 10">CLB instellingen gedaan</span>  
- [ ] <span title="Laat een Kadex testmelding versturen en controleer ontvangst">Kadex meldingen getest</span>  
- [ ] <span title="Voer een testgesprek uit via Linphone">Linphone testgesprek gelukt</span>  
- [ ] <span title="Controleer of DAVx5 succesvol synchroniseert">DAVx5 synchronisatie getest</span>  

---

**Voltooiing:** Zodra deze checklist volledig is gecontroleerd, kan de gebruiker verder met de **handleiding voor configuratie**.  

---

# 📘 Configuratie Handleiding – CLB, Kadex, WebDAV & Linphone

---

## 7. Kadex Configureren

1. Open **Kadex Notifier**.
2. Vul het **serveradres** in: `10.99.0.3`
3. Pas de **naam** aan indien nodig.
4. Sla de instellingen op.

 ---

## 8. WebDAV Configureren (DAVx5)

1. Open **DAVx5**.
2. Voeg een **nieuwe WebDAV-account** toe.
3. Vul in: - **Server:** `http://10.10.14.176/`
- **Gebruikersnaam:** `Vraag aan vab`
- **Wachtwoord:** `Vraag aan vab`

3. Pas de **naam** aan indien nodig.
4. Sla de instellingen op.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/15.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/16.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/17.png)

---

## 9. 4G & Linphone Correct Instellen

1. Open **Linphone CLB**.
2. Configureer Linphone met: - **Server:** `10.10.20.12`
- **Transport:** `UDP`
3. Sluit de Linphone-app **volledig af**.
4. Zet **4G weer AAN**.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/9836067b3c8d9fa5fb7e3b00ecfc9b3a2556b92d/18.png)

---

## 10. CLB App Afronden

1. Open **CLB Messenger**.
2. Voer bij de **naam van de gebruiker en code** niks in klik boven in rechts 3 keer.
3. Vul bij **WiFi serveradres** in: `amsta.hosting.clb.nl`
4. Zet het vinkje **“WiFi only” UIT**.
5. Vul bij **Mobile serveradres** opnieuw in: `amsta.hosting.clb.nl`
6. Tik op **Bevestigen**.

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/1.png)
![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/1495772b93ef6ce464f6955ab0e046f4eb1992e0/4.png)

---

## 11. Video Call Test – Google Meet

1. Open **Google Meet** op een ander apparaat (telefoon of laptop).
2. Tik op **Nieuwe vergadering**.
3. Kies **Een vergadering starten**.
4. Kopieer de **vergaderlink** of **10-cijferige lettercode**.
5. Open **Google Meet** op de **Samsung XCover 7**.
6. Tik op **Code invoeren** of **Deelnemen**.
7. Plak of typ de **10-cijferige code** of open de **link**.
8. Tik op **Deelnemen**.

  ![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/e159cd1defd373a8721f940525b9c832fb48de22/23%20(1).png)
  ![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/e159cd1defd373a8721f940525b9c832fb48de22/22.jpg)
  ![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/e159cd1defd373a8721f940525b9c832fb48de22/24.png)

  ---

## 12. Eindcontrole – Toestel Gereed

- [ ] <span title="Verstuur en ontvang een testbericht">CLB werkt correct</span>  
- [ ] <span title="Laat een testmelding versturen">Kadex meldingen komen binnen</span>  
- [ ] <span title="Bel uitgaand en neem inkomend gesprek aan">Linphone kan bellen</span>  
- [ ] <span title="Controleer of synchronisatie zonder fouten loopt">WebDAV synchroniseert</span>  
- [ ] <span title="Voer een test videogesprek">Google Meet getest</span>  
  
---

✅ **Toestel is nu volledig klaar voor gebruik binnen Amsta Zorg.**
