# ⚡ Joc-EDA-FIB (QT 24-25) - Edició *Harry Potter*

[![HitCount](https://hits.dwyl.com/amara213/Joc-EDA-FIB.svg?style=flat-square)](http://hits.dwyl.com/amara213/Joc-EDA-FIB)  
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](/CONTRIBUTING.md)  
[![GitHub stars](https://img.shields.io/github/stars/amara213/Joc-EDA-FIB.svg)](https://github.com/amara213/Joc-EDA-FIB/stargazers)  
[![GitHub forks](https://img.shields.io/github/forks/amara213/Joc-EDA-FIB.svg)](https://github.com/amara213/Joc-EDA-FIB/network)  
[![Repo size](https://img.shields.io/github/repo-size/amara213/Joc-EDA-FIB.svg)](https://github.com/amara213/Joc-EDA-FIB)

---

## 🧙‍♂️ Comparteix la teva màgia!

Si tu també vas participar al torneig d’EDA del **quadrimestre de primavera 2024-2025**, t’animo a que comparteixis la teva IA basada en el món de **Harry Potter** (pull requests, issues o missatge directe benvinguts!).

---

## 🧩 Sobre el joc

Aquest any el joc dissenyat pel professor Martí Oller s’inspira en el món màgic de Harry Potter. Cada jugador controla una sèrie de personatges que han de capturar punts estratègics al mapa (com Hogsmeade, Hogwarts, Gringotts, etc.) mentre lluiten contra forces fosques i altres IA.

Els objectius són:
- Controlar territoris màgics
- Evitar els encanteris dels rivals
- Maximitzar punts a través de la connectivitat màgica

Consulta les [normes oficials](rules.pdf) per entendre el funcionament complet del joc.

---

## 🧠 Crea la teva IA

El punt de partida per desenvolupar la teva estratègia és el fitxer `AIDemo.cc`, on podràs definir el comportament dels teus mags i bruixes.

Per compilar el projecte:

```bash
cp AIDummy.o.Linux64 AIDummy.o
make
````
Per veure quins jugadors tens disponibles:

````bash
./Game -l
````
Per fer una partida:

````bash
./Game -s 123 Nom Dummy Dummy Dummy < default.cnf > default.out
