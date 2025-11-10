# 💼 Loan Prediction – Machine Learning Project

### 🎓 Masterschool Mock Interview Project by *Julia Felgentreu*

---

## 📖 Projektübersicht

Dieses Projekt entstand im Rahmen meines **finalen Mock-Interviews bei Masterschool**.  
Ziel war es, mithilfe von Machine Learning vorherzusagen, **ob ein Kreditantrag genehmigt oder abgelehnt wird**.

Dabei lag mein Fokus nicht nur auf der Modellgenauigkeit, sondern darauf,  
**einen klaren, strukturierten und nachvollziehbaren Analyseprozess** zu zeigen.

---

## 🧭 Ziele des Projekts

- 🧹 Daten aufbereiten und bereinigen  
- 🔍 Explorative Datenanalyse durchführen  
- 🔢 Kategorische Variablen encodieren  
- 🌳 Klassifikationsmodell (Decision Tree) trainieren  
- 📈 Modellleistung evaluieren & interpretieren  
- 🧠 Wichtigste Einflussfaktoren identifizieren  

---

## 💾 Datensatz

**Quelle:** Masterschool Mock Interview Dataset  
**Größe:** 563 Zeilen · 13 Spalten  

| Spalte | Beschreibung |
|--------|---------------|
| `loan_id` | Eindeutige Kredit-ID |
| `gender` | Geschlecht |
| `married` | Familienstand |
| `dependents` | Anzahl der unterhaltsberechtigten Personen |
| `education` | Bildungsstatus |
| `self_employed` | Selbstständig (Ja/Nein) |
| `applicant_income` | Einkommen des Antragstellers |
| `coapplicant_income` | Einkommen des Mit-Antragstellers |
| `loan_amount` | Kreditsumme (in Tausend) |
| `loan_amount_term` | Laufzeit des Kredits (Monate) |
| `credit_history` | Kredit-Historie (1 = gut, 0 = schlecht) |
| `property_area` | Gebiet (Urban / Semi Urban / Rural) |
| `loan_status` | Zielvariable (1 = bewilligt, 0 = abgelehnt) |

---

## ⚙️ Vorgehensweise

1. **Datenexploration** – Überblick über Struktur, Datentypen & fehlende Werte  
2. **Data Cleaning** – Fehlende Werte mit Median/Modus ersetzt  
3. **Encoding** – Kategorische Variablen per *One-Hot-Encoding* umgewandelt  
4. **Train/Test Split** – 80/20-Aufteilung für Training & Evaluation  
5. **Modelltraining** – Decision Tree Classifier verwendet  
6. **Evaluation** – Accuracy, Confusion Matrix, Feature Importance analysiert  

---

## 🌳 Modell & Ergebnisse

- **Algorithmus:** Decision Tree Classifier  
- **Accuracy:** ~80 %  
- **Confusion Matrix:** Zeigt, dass bewilligte Kredite sehr gut erkannt werden  
- **Top Features:** Kredit-Historie, Kreditsumme, Einkommen  

### 🔍 Insights
- Eine gute Kredit-Historie ist der stärkste Indikator für Kreditbewilligung.  
- Einkommen & Kreditsumme spielen ebenfalls eine zentrale Rolle.  
- Weitere Merkmale wie Familienstand oder Se
