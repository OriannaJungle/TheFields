---
title: Les 1 Dynamica
tags:
  - Dynamica
---
# Kinetische energie en arbeid

# Dynamica & Energie

### 1. Arbeid (Work)
$$
\begin{aligned}
& U = F \cdot s && \text{Arbeid lineair (kracht // verplaatsing)} \\
& U = F \cdot s \cdot \cos(\alpha) && \text{Arbeid met kracht onder hoek } \alpha \\
& U = M \cdot \theta && \text{Arbeid bij rotatie (Moment } M \text{ over hoek } \theta \text{ in rad)}
\end{aligned}
$$

### 2. Kinetische Energie ($T$)
$$
\begin{aligned}
& T_{trans} = \frac{1}{2} m v^2 && \text{Kinetische energie (translatie)} \\
& T_{rot} = \frac{1}{2} I \omega^2 && \text{Kinetische energie (rotatie)} \\
& U_{totaal} = \Delta T && \text{Arbeid-energietheorema: } U_{tot} = T_{na} - T_{voor}
\end{aligned}
$$

### 3. Veer
$$
\begin{aligned}
& \Delta V_{veer} = \frac{1}{2} k (s_1^2 - s_2^2) && \text{Verandering in potentiële veerenergie} \\
& V_{veer} = \frac{1}{2} k s^2 && \text{Potentiële elastische energie (opgeslagen)} \\
& F_{veer} = k \cdot s && \text{Wet van Hooke (waarbij } s \text{ de verlenging is)}
\end{aligned}
$$

### 4. Relatie Lineair & Rotatie 
$$
\begin{aligned}
& v = \omega \cdot r && \text{Snelheid uitgedrukt in hoeksnelheid en straal} \\
& s_{boog} = \theta \cdot r && \text{Afgelegde weg langs een cirkelboog}
\end{aligned}
$$

### 5. Massatraagheidsmoment ($I$)
$$
\begin{aligned}
& I = m r_{g}^2 && \text{Puntmassa of dunne ring} \\
& I_{schijf} = \frac{1}{2} m r^2 && \text{Massieve cilinder / schijf} \\
& I_{bol} = \frac{2}{5} m r^2 && \text{Massieve bol} \\
& I_{staaf} = \frac{1}{12} m L^2 && \text{Dunne staaf (as door midden)} \\
& I_{Steiner} = I_G + m d^2 && \text{Wet van Steiner (as op afstand } d \text{ van zwaartepunt } G\text{)}
\end{aligned}
$$

---

### Betekenis van de Symbolen

| Symbool | Betekenis | Eenheid (SI) | Toelichting |
| :--- | :--- | :--- | :--- |
| $U$ (of $W$) | **Arbeid** | Joule ($J$ of $Nm$) | De hoeveelheid overgedragen energie. |
| $F$ | **Kracht** | Newton ($N$) | De lineaire inspanning op een voorwerp. |
| $s$ | **Verplaatsing** | Meter ($m$) | De afgelegde afstand of verlenging van een veer. |
| $M$ (of $\tau$) | **Krachtmoment** | Newtonmeter ($Nm$) | De draaikracht (Torque). |
| $\theta$ | **Hoekverdraaiing** | Radiaal ($rad$) | De draaiing ($2\pi \text{ rad} = 360^{\circ}$). |
| $T$ (of $E_k$) | **Kinetische Energie** | Joule ($J$) | De energie die een voorwerp heeft door beweging. |
| $m$ | **Massa** | Kilogram ($kg$) | De hoeveelheid materie (traagheid bij translatie). |
| $v$ | **Snelheid** | Meter per seconde ($m/s$) | De lineaire snelheid. |
| $I$ | **Massatraagheidsmoment** | $kg \cdot m^2$ | De weerstand tegen hoekversnelling. |
| $\omega$ | **Hoeksnelheid** | Rad/seconde ($rad/s$) | Hoe snel iets draait (omega). |
| $\alpha$ | **Hoek** | Graden ($^{\circ}$) | De hoek tussen de kracht $F$ en de weg $s$. |
| $r$ | **Straal** | Meter ($m$) | Afstand van de as tot de massa (radius). |
| $L$ | **Lengte** | Meter ($m$) | De totale lengte van een staaf of object. |
| $d$ | **Afstand** | Meter ($m$) | Verschuiving van de as bij de Wet van Steiner. |
| $k$ | **Veerconstante** | $N/m$ | De stijfheid van een veer. |
| $\Delta$ | **Delta** | - | Symbool voor "verandering in" ($Na - Voor$). |

> [!TIP] Substitutie: Snelheid naar Rotatie
> ### 
Wanneer een puntmassa op een afstand $r$ van een as draait, kan je de lineaire snelheid $v$ vervangen door de hoeksnelheid $\omega$ met de relatie:
$$v = \omega \cdot r$$
Als je dit invult in de formule voor translatie kinetische energie:
$$T_{trans} = \frac{1}{2} m v^2$$
Krijg je:
$$T = \frac{1}{2} m (\omega \cdot r)^2 \implies T = \frac{1}{2} (m r^2) \omega^2$$
**Conclusie:**
Omdat $I = m r^2$ voor een puntmassa, zie je dat $T_{trans}$ overgaat in de formule voor rotatie-energie:
$$T_{rot} = \frac{1}{2} I \omega^2$$

# Bewegingsvergelijkingen voor Translatie

### 1. Kernformules (Tweede Wet van Newton)
$$
\begin{aligned}
& \sum F_x = m \cdot a_x && \text{Som van de krachten in de x-richting} \\
& \sum F_y = m \cdot a_y && \text{Som van de krachten in de y-richting} \\
& F_w = f \cdot F_N && \text{Wrijvingskracht (met wrijvingscoëfficiënt } f \text{)} \\
& F_z = m \cdot g && \text{Zwaartekracht}
\end{aligned}
$$

### 2. Oplosmethode: Vrij Lichaamsschema (VLS)
Voor dit type vraagstuk (blok verbonden met touw aan emmer/steen) volg je deze stappen:

**Voor het blok (horizontaal):**
$$
\begin{aligned}
& \sum F_y = 0 \implies F_N = m_{blok} \cdot g && \text{(Berekenen normaalkracht)} \\
& \sum F_x = T - F_w = m_{blok} \cdot a && \text{(Vergelijking 1: Spankracht minus wrijving)}
\end{aligned}
$$

**Voor de emmer/steen (verticaal):**
$$
\begin{aligned}
& \sum F_y = m_{steen} \cdot g - T = m_{steen} \cdot a && \text{(Vergelijking 2: Zwaartekracht minus spankracht)}
\end{aligned}
$$

**Kracht op de steen:**
$$
\begin{aligned}
& \sum F_{steen} = m_{steen} \cdot g - F_{contact} = m_{steen} \cdot a && \text{(Interne kracht tussen emmer en steen)}
\end{aligned}
$$

---

### Betekenis van de Symbolen

| Symbool        | Betekenis                | Eenheid         | Toelichting                                   |
| :------------- | :----------------------- | :-------------- | :-------------------------------------------- |
| $\sum F$       | **Nettokracht**          | Newton ($N$)    | De som van alle krachten op een object.       |
| $m$            | **Massa**                | Kilogram ($kg$) | Massa van het blok, de emmer of de steen.     |
| $a$            | **Versnelling**          | $m/s^2$         | De versnelling van het gehele systeem.        |
| $T$            | **Spankracht**           | Newton ($N$)    | Kracht in het touw (Tension).                 |
| $F_N$          | **Normaalkracht**        | Newton ($N$)    | Kracht loodrecht op het oppervlak.            |
| $F_w$          | **Wrijvingskracht**      | Newton ($N$)    | Tegenwerkende kracht van de ondergrond.       |
| $f$ (of $\mu$) | **Wrijvingscoëfficiënt** | -               | Mate van gladheid tussen oppervlakken.        |
| $g$            | **Valversnelling**       | $m/s^2$         | $9,81 m/s^2$ op aarde.                        |
| $F_{contact}$  | **Contactkracht**        | Newton ($N$)    | De kracht die de emmer op de steen uitoefent. |
|                |                          |                 |                                               |

https://www.studeersnel.nl/nl/document/berlage-lyceum/natuurkunde/hoofdstuk-newton/77537330

### 1. Eerste Wet: Wet van de Traagheid
> "Een voorwerp blijft in rust of beweegt met een constante snelheid, tenzij er een netto kracht op werkt."

**In formulevorm:**
$$ \sum F = 0 \implies v = \text{constant} $$
*   **Toepassing:** Als een blok met constante snelheid over de tafel schuift, weet je dat de trekkracht precies gelijk is aan de wrijvingskracht ($T = F_w$).

### 2. Tweede Wet: Grondwet van de Dynamica
> "De versnelling van een voorwerp is recht evenredig met de nettokracht en heeft dezelfde richting als deze kracht."

**In formulevorm:**
$$ \sum F = m \cdot a $$
*   **Toepassing:** Dit is de basis voor je berekeningen in Hoofdstuk 4. Je gebruikt dit om de versnelling ($a$) van het systeem te bepalen door de krachten op het blok en de emmer te sommeren.

### 3. Derde Wet: Wet van Actie en Reactie
> "Als voorwerp A een kracht uitoefent op voorwerp B, dan oefent voorwerp B een even grote, maar tegengestelde kracht uit op voorwerp A."

**In formulevorm:**
$$ F_{actie} = -F_{reactie} $$
*   **Toepassing:** 
    *   De **spankracht ($T$)** in het touw: het touw trekt even hard aan het blok als aan de emmer.
    *   De **normaalkracht ($F_N$)**: de tafel duwt even hard omhoog als het blok omlaag duwt.
    *   De **contactkracht**: de steen duwt op de emmer, en de emmer duwt terug op de steen.