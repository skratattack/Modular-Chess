# Modular Chess – Anleitung

**Version:** 1.0  
**Stand:** Mai 2026  
**Autor:** Aron Lange  
**Lizenz:** CC BY-NC-SA 4.0  

---

## Abstract

> *Was wäre, wenn deine Figuren nicht nur ziehen, sondern sich auch verwandeln könnten?
> Modular Chess nimmt das klassische Schach, zerlegt jede Figur in ihre Bestandteile
> und gibt dir die Macht, mitten im Spiel Material umzuverteilen. Dein Läufer und dein
> Springer verschmelzen zum Turm. Deine Dame spaltet sich in zwei Türme auf.
> Klingt nach Chaos? Ist es auch – aber mit Regeln.
> Willkommen beim Schach für Leute, denen das klassische Spiel
> noch nicht genug Möglichkeiten bietet, sich falsch zu entscheiden. ;D*

---

## Inhaltsverzeichnis

1. [Einleitung & Überblick](#1-einleitung--überblick)
2. [Das Materialsystem](#2-das-materialsystem)
3. [Startaufstellung](#3-startaufstellung)
4. [Zugregeln – Das klassische Fundament](#4-zugregeln--das-klassische-fundament)
5. [Die neue Regel: Transformation](#5-die-neue-regel-transformation)
6. [Sonderregeln & Einschränkungen](#6-sonderregeln--einschränkungen)
7. [Notation](#7-notation)
8. [Strategie-Tipps](#8-strategie-tipps)
9. [Materialübersicht](#9-materialübersicht)

---

## 1. Einleitung & Überblick

Modular Chess ist eine Schachvariante, die auf dem klassischen Schachspiel aufbaut.
Brett, Startaufstellung und Zugregeln bleiben vollständig erhalten – es kommt lediglich
eine neue Zugmöglichkeit hinzu: die **Transformation**.

Dabei werden Figurenwerte in Form von physischen **Modulplättchen** zwischen eigenen
Figuren übertragen. Ein Springer kann seinen Wert an einen Bauern abgeben, zwei
Leichtfiguren können zu einem Turm verschmelzen, eine Dame kann sich in zwei Türme
aufspalten.

Das Besondere: Die Spielfiguren sind so konstruiert, dass jede Transformation auch
physisch am Brett sichtbar vollzogen wird. Jede Figur (außer dem König) besteht aus
einem **Grundbauern** und bis zu vier **Modulplättchen**, die in Schlitze gesteckt werden.

**Voraussetzung:** Kenntnisse der klassischen Schachregeln.

---

## 2. Das Materialsystem

### 2.1 Der Grundbauer

Die Basis jeder Figur (außer dem König) ist der **Grundbauer** – ein zylindrischer
Figurenkörper mit vier vertikalen Schlitzen, die kreuzförmig um die Mittelachse
angeordnet sind. Die Schlitze sind in der Mitte **nicht** miteinander verbunden,
sodass der Figurenkörper seine strukturelle Stabilität behält.

<!-- 📸 Abbildung 1: Grundbauer mit vier Schlitzen – Draufsicht und Seitenansicht -->
<img src="img/01_grundbauer.png" width="200">

*Abb. 1: Der Grundbauer. Links: Draufsicht mit kreuzförmiger Schlitzanordnung.
Rechts: Seitenansicht.*

### 2.2 Die Modulplättchen

Es gibt genau zwei Arten von Modulplättchen:

- **Springer-Modul:** Die Silhouette zeigt die charakteristische Form eines
  Springerkopfes.
- **Läufer-Modul:** Die Silhouette zeigt die charakteristische Mitra (Spitze)
  eines Läufers.

Beide Plättchen sind so dimensioniert, dass sie passgenau in die Schlitze des
Grundbauern geschoben werden können. Jedes Modulplättchen repräsentiert einen
**Materialwert von 2 Punkten**.

<!-- 📸 Abbildung 2: Springer-Modul und Läufer-Modul – Vorder- und Rückseite -->
<img src="img/02_modulplaettchen.png" width="200">

*Abb. 2: Links: Läufer-Modul. Rechts: Springer-Modul.*

### 2.3 Figurenaufbau

Durch das Einstecken der Modulplättchen in den Grundbauern entstehen alle
klassischen Schachfiguren:

| Figur | Zusammensetzung | Materialwert | Aufbau |
|-------|----------------|--------------|--------|
| **Bauer** | Grundbauer (ohne Module) | 1 | – |
| **Springer** | Grundbauer + 1 Springer-Modul | 3 (1+2) | Modul in einem Schlitz, Springerkopf nach außen sichtbar |
| **Läufer** | Grundbauer + 1 Läufer-Modul | 3 (1+2) | Modul in einem Schlitz, Mitra nach außen sichtbar |
| **Turm** | Grundbauer + 2 beliebige Module | 5 (1+2+2) | Module um 180° gedreht in gegenüberliegende Schlitze (Startaufstellung: 1S + 1L)|
| **Dame** | Grundbauer + 4 beliebige Module | 9 (1+4×2) | Alle 4 Module an der Unterseite als „Stelzen"  (Startaufstellung: 2S + 2L)|
| **König** | Klassische Figur (nicht modular) | – | Keine Module |

#### Der Springer

Ein Springer-Modul wird mit der Silhouette nach außen in einen der vier Schlitze
gesteckt. Die resultierende Figur ist durch den erkennbaren Springerkopf eindeutig
identifizierbar.

<!-- 📸 Abbildung 3: Aufbau Springer -->
<img src="img/03_springer.png" width="200">

*Abb. 3: Zusammenbau eines Springers. Der Springerkopf ist als Silhouette klar
erkennbar.*

#### Der Läufer

Analog zum Springer wird ein Läufer-Modul mit der Mitra-Spitze nach außen in einen
Schlitz gesteckt.

<!-- 📸 Abbildung 4: Aufbau Läufer -->
<img src="img/04_laeufer.png" width="200">

*Abb. 4: Zusammenbau eines Läufers. Die Läuferspitze (Mitra) ist als Silhouette
klar erkennbar.*

#### Der Turm

Für den Turm werden ein Springer-Modul und ein Läufer-Modul jeweils **um 180°
gedreht** in zwei gegenüberliegende Schlitze gesteckt. Dadurch zeigen die
**Rückseiten** der Plättchen nach außen. Diese sind so gestaltet, dass sie gemeinsam
die typische Zinnen-Kontur eines Turms nachbilden. Gleichzeitig unterscheidet sich
die Figur durch die gedrehte Einbaurichtung deutlich von Springer und Läufer.
In der Startaufstellung bestehen alle Türme aus jeweils einem Springer- und einem Läufer-Modul.

<!-- 📸 Abbildung 5: Aufbau Turm – mit Detailansicht der Rückseiten -->
<img src="img/05_turm.png" width="200">

*Abb. 5: Zusammenbau eines Turms. Die umgedrehten Module bilden durch ihre
Rückseiten die Turm-Silhouette. Detail: Springerkopf zeigt nach innen,
Turmzinne nach außen.*

#### Die Dame

Die Dame besteht aus allen vier Modulplättchen, die
an der **Unterseite** des Grundbauern befestigt werden. Die Module werden verdreht
angebracht und dienen als „Stelzen", wodurch die Dame deutlich höher steht als
alle anderen Figuren und sofort erkennbar ist. Die Anordnung der Module an der
Unterseite ist beliebig. In der Startaufstellung bestehen die Damen jeweils aus
zwei Springer- und zwei Läufer-Modulen.

<!-- 📸 Abbildung 6: Aufbau Dame -->
<img src="img/06_dame.png" width="200">

*Abb. 6: Zusammenbau einer Dame. Die vier Module als „Stelzen" an der Unterseite heben die Figur deutlich vom Brett ab.*

#### Der König

Der König ist die einzige nicht-modulare Figur. Er behält seine klassische Form
und nimmt nicht am Transformationssystem teil.

---

<!-- 📸 Abbildung 7: Alle Figuren nebeneinander -->
<img src="img/07_alle_figuren.png" width="600">

*Abb. 7: Alle Figurentypen im direkten Vergleich (v.l.n.r.): Bauer, Springer,
Läufer, Turm, Dame, König.*

---

## 3. Startaufstellung

Die Startaufstellung ist **identisch zum klassischen Schach**. Alle Figuren stehen
in ihrer vollständig zusammengesetzten Form auf dem Brett.

<!-- 📸 Abbildung 8: Startaufstellung -->
<img src="img/08_startaufstellung.png" width="600">

*Abb. 8: Startaufstellung. Identisch zum klassischen Schach.*

---

## 4. Zugregeln – Das klassische Fundament

Alle Figuren ziehen und schlagen **exakt wie im klassischen Schach**:

- Der **Bauer** zieht einen Schritt vorwärts (zwei vom Startfeld), schlägt diagonal.
- Der **Springer** zieht im L-förmigen Muster und springt über andere Figuren.
- Der **Läufer** zieht diagonal beliebig weit.
- Der **Turm** zieht horizontal und vertikal beliebig weit.
- Die **Dame** zieht horizontal, vertikal und diagonal beliebig weit.
- Der **König** zieht einen Schritt in jede Richtung.

**Schach**, **Schachmatt**, **Patt**, **En passant** und **Rochade** gelten unverändert
(mit den in Abschnitt 6 genannten Einschränkungen).

Eine vollständig reguläre Schachpartie ist in dieser Variante jederzeit möglich.

---

## 5. Die neue Regel: Transformation

### 5.1 Grundprinzip

Wenn ein Spieler am Zug ist, hat er neben einem normalen Zug eine zusätzliche
Möglichkeit: Er darf **Modulplättchen von einer eigenen Figur auf eine andere
eigene Figur übertragen**. Dies nennt sich **Transformation** und ersetzt in diesem
Zug den normalen Zug – es ist also entweder ein normaler Zug ODER eine
Transformation erlaubt.

### 5.2 Bedingungen

Eine Transformation ist an folgende Bedingungen geknüpft:

1. **Reichweite:** Die abgebende Figur muss das Feld der empfangenden Figur mit
   ihrem aktuellen Zugmuster **erreichen können** – so, als würde sie eine
   gegnerische Figur auf diesem Feld schlagen wollen. Alle normalen Zugregeln
   gelten (z.B. darf ein Läufer nicht durch andere Figuren hindurchziehen).

2. **Ein Zielfeld:** Pro Transformation darf nur **ein einziges Zielfeld**
   ausgewählt werden. Module dürfen nicht in einem Zug auf mehrere Felder
   verteilt werden.

3. **Gültige Ergebnisse:** Auf beiden betroffenen Feldern (Ausgangs- und Zielfeld)
   müssen nach der Transformation **gültige Figuren** entstehen, die im
   klassischen Schach existieren (Bauer, Springer, Läufer, Turm oder Dame).

4. **Freie Wahl der Module:** Der Spieler entscheidet selbst, **welche und wie
   viele** Module übertragen werden – solange die Bedingungen 2 und 3 erfüllt
   sind.

5. **König ausgenommen:** Der König kann weder Module abgeben noch empfangen.

### 5.3 Beispiele

#### Beispiel 1: Fusion (Läufer + Springer → Turm)

Ein weißer **Läufer** steht auf a2, ein weißer **Springer** auf b3.
Der Läufer kann das Feld b3 diagonal erreichen.

**Transformation:** Das Läufer-Modul wird von a2 nach b3 übertragen.

**Ergebnis:**
- Feld a2: Grundbauer (ohne Module) → **Bauer**
- Feld b3: Grundbauer + Springer-Modul + Läufer-Modul → **Turm**

<!-- 📸 Abbildung 9: Beispiel Fusion -->
<img src="img/09_beispiel_fusion.png" width="600">

*Abb. 9: Transformation – Fusion. Der Läufer auf a2 überträgt sein Modul auf den
Springer auf b3. Ergebnis: Bauer auf a2, Turm auf b3.*

#### Beispiel 2: Aufspaltung (Dame → Turm + Turm)

Eine weiße **Dame** steht auf d1, ein weißer **Bauer** auf e2.
Die Dame kann das Feld e2 diagonal erreichen.

**Transformation:** Zwei Module werden von d1 nach e2 übertragen.

**Ergebnis (Variante A – gemischte Türme):**
- Feld d1: Grundbauer + 1 Springer-Modul + 1 Läufer-Modul → **Turm**
- Feld e2: Grundbauer + 1 Springer-Modul + 1 Läufer-Modul → **Turm**

**Ergebnis (Variante B – gleichartige Türme):**
- Feld d1: Grundbauer + 2 Springer-Module → **Turm**
- Feld e2: Grundbauer + 2 Läufer-Module → **Turm**

Der Spieler wählt frei, welche Module übertragen werden. Spielmechanisch sind
beide Varianten vorerst identisch (beide Figuren sind Türme). Dies ändert sich aber sobald die Türme erneut aufgespalten werden
und unterschiedliche Leichtfiguren zurückbleiben.

<!-- 📸 Abbildung 10: Beispiel Aufspaltung -->
<img src="img/10_beispiel_aufspaltung.png" width="600">

*Abb. 10: Transformation – Aufspaltung. Die Dame auf d1 überträgt zwei Module
auf den Bauern auf e2. Ergebnis: Zwei Türme.*

#### Gegenbeispiel: Mehrere Zielfelder (❌ verboten)

Eine weiße Dame steht auf d1, weiße Bauern auf c2, d2 und e2.
Die Dame könnte alle drei Felder erreichen.

**NICHT erlaubt:** Module auf c2 UND e2 gleichzeitig verteilen.
Es darf pro Zug nur **ein** Zielfeld gewählt werden.

<!-- 📸 Abbildung 11: Gegenbeispiel -->
<img src="img/11_gegenbeispiel.png" width="600">

*Abb. 11: Verboten – Module dürfen nicht in einem Zug auf mehrere Felder
verteilt werden.*

---

## 6. Sonderregeln & Einschränkungen

### 6.1 Rochade

Die Rochade ist nur mit **Original-Türmen** erlaubt, die seit Spielbeginn **nicht
an einer Transformation beteiligt waren** – weder als abgebende noch als
empfangende Figur. Sobald ein Turm Module abgibt oder erhält, verliert er
dauerhaft das Rochaderecht.

### 6.2 Keine Bauern auf der Grundreihe

Durch eine Transformation darf **kein Bauer auf einer der beiden Grundreihen**
(Reihe 1 oder Reihe 8) entstehen. Eine Transformation, die einen Bauern auf
der Grundreihe erzeugen würde, ist nicht erlaubt.

*Beispiel:* Ein Turm auf a1 darf seine Module nicht vollständig an eine Figur
auf a2 abgeben, da auf a1 ein Bauer auf der eigenen Grundreihe entstehen würde.

<!-- 📸 Abbildung 12: Gegenbeispiel Grundreihe -->
<img src="img/12_gegenbeispiel_grundreihe.png" width="600">

*Abb. 12: Verboten – Durch die Transformation würde ein Bauer auf der
Grundreihe (a1) entstehen.*

### 6.3 Eingeschränkte Bauernumwandlung

Wenn ein Bauer die gegnerische Grundreihe erreicht, darf er **maximal in einen
Turm** umgewandelt werden (= erhält maximal 2 Modulplättchen). Eine Umwandlung
in eine Dame ist **nicht** erlaubt.

**Begründung:** Ohne diese Einschränkung wäre folgender Zyklus möglich:
Bauer erreicht Grundreihe → Umwandlung in Dame → ein Schritt zurück →
Module an anderen Bauern übertragen → erneut auf Grundreihe ziehen → erneute
Umwandlung. Dies würde zu einer schnellen, unkontrollierbaren
Materialvermehrung führen.

**Hinweis:** Auch mit der Beschränkung auf maximal einen Turm bei der
Umwandlung bleibt eine langfristige Materialvermehrung über diesen Zyklus
theoretisch möglich (Umwandlung in Turm → Rückzug → Module übertragen →
erneute Umwandlung). Der Zyklus ist jedoch deutlich abgeschwächt, da pro
Umwandlung nur 2 Module statt 4 gewonnen werden und jeder Durchlauf
mehrere Züge kostet – Tempo, das der Gegner nutzen kann.

### 6.4 En passant

Die En-passant-Regel gilt ausschließlich für **reguläre Bauernzüge**. Ein Bauer,
der durch eine Transformation auf einem Feld entsteht (z.B. weil eine Figur
alle Module abgibt), darf im Folgezug **nicht** en passant geschlagen werden –
auch dann nicht, wenn er auf einem Feld steht, das einem Doppelschritt
entsprechen würde.

---

## 7. Notation

### 7.1 Grundprinzip

Modular Chess verwendet die **algebraische Notation** des klassischen Schachs
als Basis. Für normale Züge ändert sich nichts. Für Transformationen wird eine
erweiterte Schreibweise eingeführt.

### 7.2 Normale Züge

Normale Züge werden wie gewohnt notiert:

| Notation | Bedeutung |
|----------|-----------|
| `e4` | Bauer zieht nach e4 |
| `Sf3` | Springer zieht nach f3 |
| `Lxc6` | Läufer schlägt auf c6 |
| `O-O` | Kurze Rochade |
| `O-O-O` | Lange Rochade |
| `e8=T` | Bauer umgewandelt in Turm auf e8 |

### 7.3 Transformationen

Transformationen werden mit folgendem Schema notiert:
```
[Ausgangsfeld]>[Zielfeld]=[Ergebnis Zielfeld]
```
Das **Ergebnis auf dem Ausgangsfeld** ergibt sich implizit (Gesamtmaterial minus
transferierte Module).

#### Figurensymbole für die Notation

| Symbol | Figur |
|--------|-------|
| `S` | Springer |
| `L` | Läufer |
| `T` | Turm |
| `D` | Dame |

#### Beispiele

| Stellung | Transformation | Notation | Ergebnis |
|----------|---------------|----------|----------|
| Läufer a2, Springer b3 | Läufer-Modul → b3 | `a2>b3=T` | Bauer a2, Turm b3 |
| Springer f3, Bauer d2 | Springer Module → d2 | `f3>d2=S` | Bauer f3, Springer d2 |
| Turm a3, Turm d3 | 2 gemischte Module → d3 | `a3>d3=D` | Bauer a3, Dame d3 |
| Turm a1, Bauer a2 | Springer-Modul → a2 | `a1>a2=S` | Läufer a1, Springer a2 |

#### Pflichtangabe bei mehrdeutigen Transformationen

Wenn eine Dame aufgeteilt wird, **müssen** die übertragenen Module an
des Zielfeld angegeben werden. Dies ist spielrelevant, da sich Türme/Damen in
späteren Zügen erneut aufteilen können und die entstehenden Leichtfiguren von
der Modulzusammensetzung abhängen.

- `(SS)` = zwei Springer-Module
- `(LL)` = zwei Läufer-Module
- `(SL)` = ein Springer-Modul + ein Läufer-Modul

Die Zusammensetzung des **Ausgangsfeld-Turms** ergibt sich implizit aus den
verbleibenden Modulen.

Bei gemischten Türmen `T(SL)` kann ein ähnlicher Fall auftreten, wenn ein Modul an eine Leichtfigur abgegeben wird.
In diesem Fall muss auch das übertragene Modul in Klammern aufgeführt werden.

**Beispiel:**

| Stellung | Notation | Ergebnis |
|----------|----------|----------|
| Dame d1(SSLL), Bauer e2 | `d1>e2=T(SS)` | Turm d1 (LL), Turm e2 (SS) |
| Dame d1(SSLL), Bauer e2 | `d1>e2=T(SL)` | Turm d1 (SL), Turm e2 (SL) |
| Dame d1(SSLL) Bauer e2 | `d1>e2=T(LL)` | Turm d1 (SS), Turm e2 (LL) |
| Dame b1(SSLL), Turm a1(SL) | `b1>a1=D(LL)` | Dame b1 (SLLL), Turm d1 (SS) |
| Turm a1(SL), Läufer b1 | `a1>b1=T(L)` | Springer a1, Turm b1 (LL) |

**Hinweis:** Bei allen anderen Transformationen ist die Modulzusammensetzung
eindeutig und muss nicht angegeben werden.

### 7.4 Vollständiges Notationsbeispiel

```
e4 e5
Sf3 Sc6
Lc4 Sf6
f3>d2=S ...  (Springer f3 überträgt Springer-Modul auf Bauer d2 → Bauer f3, Springer d2)
```
**Hinweis:** In so einem Fall können die Figuren auch vertauscht werden, anstatt das Modulplättchen umzustecken.

---

## 8. Strategie-Tipps

- **Transformation kostet Tempo:** Jede Transformation ersetzt einen normalen Zug.
  Überlege gut, ob der Positionsvorteil den Tempoverlust rechtfertigt.
- **Flexibilität bewahren:** Figuren in der Nähe eigener Bauern können sich
  jederzeit aufteilen – das schafft taktische Drohungen.
- **Türme aufteilen:** Zwei Leichtfiguren kontrollieren mehr Felder als ein Turm.
  In offenen Stellungen kann eine Aufspaltung starke Doppelangriffe ermöglichen.
- **Fusionen vorbereiten:** Zwei Leichtfiguren, die sich gegenseitig „sehen",
  können im nächsten Zug zu einem Turm verschmelzen – eine versteckte Drohung.
- **Rochaderecht beachten:** Transformationen mit den Starttürmen kosten das
  Rochaderecht. Frühes Rochieren sichert diese Option.

---

## 9. Materialübersicht

### Pro Farbe (Weiß bzw. Schwarz):

| Komponente | Anzahl |
|-----------|--------|
| König (klassisch) | 1 |
| Grundbauern (mit 4 Schlitzen) | 15 |
| Springer-Module | 6 |
| Läufer-Module | 6 |

### Gesamt:

| Komponente | Anzahl |
|-----------|--------|
| Könige | 2 |
| Grundbauern | 30 |
| Springer-Module | 12 |
| Läufer-Module | 12 |
| Schachbrett 8x8 (Feldgröße: 4-6cm) | 1 |

**Gesamtzahl Module:** 24  
**Gesamtzahl Figuren-Körper:** 32 (wie beim klassischen Schach)

## 3D-Druck

Die Figuren für Modular Chess können mit einem handelsüblichen 3D-Drucker
hergestellt werden. Die druckfertigen Dateien (STL) sind hier verfügbar:

🔗 **[Modular Chess auf MakerWorld](https://makerworld.com/de/models/DEIN-LINK)**

---

## Changelog

| Version | Datum | Änderungen |
|---------|-------|-----------|
| 1.0 | Mai 2026 | Erstveröffentlichung |

---

*© 2026 Aron Lange. Dieses Werk ist lizenziert unter
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de).*