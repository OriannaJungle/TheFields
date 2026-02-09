---
tags:
  - Duurzaam_Energietechniek
title: Les 1 duurzaam energietechniek
---
Opdrachten van duurzaam energietechniek worden via de online methode gedaan. De licentie daarvoor staat in het boek.
<span class="right-align">![[Boek energietechniek.png|300]]</span>
# inhoud algemeen
- 2 gast colleges
- 3 excursies (met gast college)
- portfolio opdracht
# inhoud les
- Inleiding duurzame energie
- begrip duurzaamheid
- 3 presentatie door studenten
- - energie verbruik
- - energievoorziening
- - energiebeleid

# Wat is duurzaamheid (volgens de klas)
- hoog rendement
- circulair: hernieuwbaar, 100!!! op termijn
- hoge product kwaliteit weinig uitstoot.
- volgende generaties kunnen gebruik maken van grondstoffen
- de aarde een natuurlijke dood laten sterven
- initieel zo min mogelijk grondstoffen gebruiken

# Les theorie

Windenergie, kinetische energie, vermogenslevering uit wind.
- wind energie
- door wind turbine ontbroken energie
- vermogen coefficient $$C_{p}$$
- Snel lopend snelheid λ

Hoeveelheid massa aanwezig in een bepaald volume

$$\rho = dichtheid = \frac{m}{V} [kg / m^3]$$

$$snel lopendsnelheid=λ=\frac{V_{tip}}{V_{wind}}$$

$$vermogenscoeficient=C_{p}=\frac{P_{trub}}{P_{wind}}$$

## Les formules
$$E_{wind}=\frac{1}{2}mv^2 [J]$$

$$E_{wind}=\frac{1}{2}m\rho^2 [J / m^3]$$

$$P_{wind}=\frac{1}{2}ϱv^3*A$$

**Waarom wil je je lopend snelheid laag hebben?**

λ is verhouding tussen snelheid van de punt van de wiek $$V_{tip}$$ en de windsnelheid $$V_{wind}$$ redenen om deze laag te houden:
- Centrifugale kracht kan de wiek breken bij een te grootte λ.
- Geluidsoverlast kan ook een reden zijn.

# opdrachten

## opdracht 1

$$P_{nominaal}​=650 W=0.65 kW$$

$$t_{jaar}​=365_{dagen}*24_{uren}=8760 h/jaar$$

$$E_{wind}= 0.65 kW * 8760 h/jaar = 5694 kWh/jaar$$

> [!TIP] $$E_{wind}$$ is niet $$E_{trubine}$$

Als de windtribune op zijn max 24/7 aan het draaien dan wekt het *5694 kWh/jaar* op.
Volgens slimster zijn de gemiddelde vollasturen als volgt:
https://slimster.nl/windturbine/opbrengst-en-vermogen-windmolen/
- Bebouwde omgeving: 500 - 1.000 uur (Veel obstakels)
- Open land (Binnenland): 1.500 - 2.000 uur
- Kustgebied: 2.200 - 2.800 uur
- Offshore (Op zee): 4.000+ uur

heel optimistisch is dat 1000 uur.

$$E_{trubine}= 0.65 kW * 1000 h/jaar = 650 kWh/jaar$$

*1.500 tot 2.500 kWh/jaar* is niet reëel.

## opdracht 2

### **a.**


$$P=?$$
---
$$P_{wind}=\frac{1}{2}ϱv^3*A$$

$$\rho = 1.2 kg/m^3$$

$$v =4m/s$$

$$A = \pi \left( \frac{46}{2} \right)^2=1661.9m^2$$

$$C_{p_{4m/s}}= 0.328$$

$$P_{wind}=\frac{1}{2}*1.2*4^3*1661.9=63816.96W$$

$$P_{trubine} = C_{p} * P_{wind}$$

$$P_{trubine}=0.328*63816.96≈20932W$$

**Vraag: Het tabel is gemeten op een hoogte van 60m, dan is deze toch niet dichtbij een echte waarde bij 2m boven de grond?**

### **b.**

#### Gegevens
$$D = 46\ \text{m}$$

$$\rho = 1.2\ \text{kg/m}^3$$

Rotoroppervlak:
$$A=\pi\left(\frac{D}{2}\right)^2$$
$$A=\pi\left(\frac{46}{2}\right)^2=\pi(23^2)=\pi\cdot 529 \approx 1661.9\ \text{m}^2$$

Vermogen turbine:
$$P_{wind}=\frac{1}{2}ϱv^3*A$$

Prijs elektriciteit:
$$\text{prijs elekektrisiteit} = 0.088\ \text{€/kWh}$$

---

#### Windsnelheid en $C_p$ per tijdsblok
- 0–6 uur: $v<2.5\ \text{m/s}$  Ik verwaarloos deze :)
- 6–10 uur: $v=4.5\ \text{m/s},\ C_p=0.399$
- 10–18 uur: $v=7\ \text{m/s},\ C_p=0.400$
- 18–21 uur: $v=4.5\ \text{m/s},\ C_p=0.399$
- 21–24 uur: $v=3.5\ \text{m/s},\ C_p=0.276$

---

#### Vermogen per dag deel


##### 6–10 uur (4 uur)
$$v=4.5,\quad C_p=0.399$$

$$P_{6-10}=\frac12 * 1.2 * 4.5^3* 1661.9  * 0.399$$


$$P_{6-10}=0.6\cdot 1661.9\cdot 91.125\cdot 0.399$$


$$P_{6-10}\approx 36191\ \text{W}=36.19\ \text{kW}$$


$$E_{6-10}=36.19\cdot 4=144.76\ \text{kWh}$$

---

$$E_{10-18}=136.83* 8=1094.64\ \text{kWh}$$

---

$$E_{18-21}=36.19* 3=108.57\ \text{kWh}$$

---

$$E_{21-24}=11.84* 3=35.52\ \text{kWh}$$

---

##### Energie totaal
$$E_{dag}=E_{6-10}+E_{10-18}+E_{18-21}+E_{21-24}$$

$$E_{dag}=144.76+1094.64+108.57+35.52$$

$$E_{dag}=1383.49\ \text{kWh}$$

$$\text{winst}_{dag}=1383.49* 0.088 = 121.$$

$$\text{€}_{dag}=121.8\ \text{€/dag}$$
