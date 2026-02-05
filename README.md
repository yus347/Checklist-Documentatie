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

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/d8766417f5554f7440a5fae8d44d4da40bd2933d/21.png)

---

### 2.2 App-rechten (machtigingen)

**Pad:** `Instellingen → Apps → [Appnaam] → Machtigingen`

- [ ] Camera → **Toegestaan**  
- [ ] Locatie → **Toegestaan**  
- [ ] Telefoon → **Toegestaan**  
- [ ] Nabije apparaten → **Toegestaan**  
- [ ] Bestanden/Media → **Toegestaan**  
- [ ] Meldingen → **Toegestaan**  

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/3f78bc6139673b6022a92dc73df3579d17f0d20e/20.png)

---

### 2.3 Batterij

**Pad:** `Instellingen → Apps → [Appnaam] → Batterij`

- [ ] Batterijgebruik → **Onbeperkt**  

![Image Alt](https://github.com/yus347/Checklist-Documentatie/blob/d8766417f5554f7440a5fae8d44d4da40bd2933d/19.png)

---

## 3. Netwerk & Functionaliteit

- [ ] WiFi verbonden  
- [ ] 4G actief  
- [ ] CLB getest via WiFi  
- [ ] CLB getest via 4G  
- [ ] Kadex meldingen getest  
- [ ] Linphone testgesprek gelukt  
- [ ] DAVx5 synchronisatie getest  

---

## 4. Vereiste systeemapps

Controleer dat deze aanwezig zijn:

- [ ] com.samsung.android.app.contacts  
- [ ] com.iqm.enterprise.smartapp  
- [ ] IQ SmartApp Enterprise  

---

**Voltooiing:** Zodra deze checklist volledig is gecontroleerd, kan de gebruiker verder met de **handleiding voor configuratie**.  

---

# 📘 Configuratie Handleiding – CLB, Kadex, WebDAV & Linphone

## 5. Servergegevens

Gebruik **altijd exact deze instellingen**:

### CLB
- **Server:** `amsta.hosting.clb.nl`

### Kadex
- **Server:** `10.99.0.3`

### WebDAV
- **Server:** `http://10.10.14.176/`
- **Gebruikersnaam:** `Schutse`
- **Wachtwoord:** `ZgKdx-j7Sd5-635DP-AEiyx-iD8cn`

### Linphone
- **Server:** `10.10.20.12`
- **Transport:** `UDP`

---

## 6. CLB App Afronden

1. Open **CLB Messenger**.
2. Voer bij de **naam van de gebruiker en code** niks in klik boven in rechts 3 keer.
3. Vul bij **WiFi serveradres** in:
4. Zet het vinkje **“WiFi only” UIT**.
5. Vul bij **Mobile serveradres** opnieuw in:
6. Tik op **Bevestigen**.

(https://github.com/yus347/Checklist-Documentatie/blob/d269624511cfeb6bd3f387da0528d7ba37dbc0f4/1.png)


---

## 7. Niet Storen (DND) Instellen voor CLB

1. Ga naar **Instellingen**.
2. Open **Apps**.
3. Tik rechtsboven op **⋮ (3 puntjes)**.
4. Kies **Speciale app-machtigingen**.
5. Ga naar **Niet storen (DND)**.
6. Zoek **CLB Messenger** en zet deze op **Toegestaan**.

📸 *Voeg hier een screenshot toe van correcte DND instellingen*

---

## 8. Kadex Configureren

1. Open **Kadex Notifier**.
2. Vul het **serveradres** in:
