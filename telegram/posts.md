# Le Terminal — posts Telegram

Canal : https://t.me/leterminalfx · communauté + signaux.

Neuf posts, pas un de plus. Chaque post est prêt à copier-coller : remplacez les valeurs `[ENTRE CROCHETS]`.

**Mise en forme Telegram** : `**gras**`, `__italique__` et `` `code` `` sont convertis par l'application au moment de l'envoi. Les chiffres en `code` s'affichent en police mono, alignés et faciles à copier.

**Règles de style (charte Le Terminal)** : on vouvoie, zéro emoji (glyphes autorisés : ▲ ▼ ✓ ✕ → —), chiffres au format français (`2 345,50`), ton direct et feutré, pas de points d'exclamation.

**Visuels** : `telegram/visuels/` contient les images génériques (sans chiffres), au format 1280 × 720 : `signal.png`, `tp1.png`, `be.png` (stop au point d'entrée), `tp2.png`, `tp3.png`, `sl.png` et `be-sortie.png` (sortie au point d'entrée après TP1). Pour une image avec les chiffres du trade, ouvrez `/telegram/generateur.html`, choisissez l'état, saisissez les valeurs et téléchargez le PNG. Envoyez l'image **avec** le texte en légende (une légende fait 1 024 caractères maximum, tous les posts de suivi tiennent dedans).

**Fil d'un trade** : publiez le signal, puis répondez au message du signal (« Répondre ») pour chaque suivi. Le fil reste lisible et chaque mise à jour renvoie au trade d'origine.

| # | Post | Quand | Visuel |
|---|---|---|---|
| 1 | Bienvenue et règles | Une fois, épinglé | — |
| 2 | Nouveau signal | À l'ouverture du trade | `signal.png` ou générateur (+ capture du graphique, facultatif) |
| 3 | TP1 atteint | TP1 touché | `tp1.png` ou générateur |
| 4 | Stop au point d'entrée (BE) | Juste après TP1 | `be.png` ou générateur |
| 5 | TP2 atteint | TP2 touché | `tp2.png` ou générateur |
| 6 | TP3 atteint, trade clôturé | TP3 touché | `tp3.png` ou générateur |
| 7 | Stop loss touché | SL touché | `sl.png` ou générateur |
| 7 bis | Sortie au point d'entrée | Retour sur l'entrée après TP1 | `be-sortie.png` ou générateur |
| 8 | Les outils du Terminal | 1 fois par semaine maximum | Capture d'un outil (facultatif) |
| 9 | Nouvel article du blog | À chaque article | Bannière de l'article |

---

## 1. Bienvenue et règles (message épinglé)

```
**BIENVENUE SUR LE TERMINAL**

Vous êtes au bon endroit pour trader avec méthode : des signaux expliqués, une gestion du risque stricte et une communauté qui progresse ensemble.

**CE QUE VOUS TROUVEREZ ICI**
— Les signaux : actif, sens, entrée, 3 objectifs (TP1, TP2, TP3) et un stop loss, toujours définis avant l'entrée.
— Le suivi en direct de chaque trade, en réponse au signal d'origine.
— Les nouveaux articles du blog et les mises à jour des outils.

**COMMENT LIRE UN SIGNAL**
TP1 atteint → le stop passe au point d'entrée, le trade ne peut plus être perdant.
TP2 atteint → la position restante court vers l'objectif final.
TP3 atteint → trade clôturé en totalité.
SL touché → perte limitée, définie à l'avance. On passe au suivant.

**LES RÈGLES**
1. Ne risquez jamais plus de 1 % de votre capital par trade.
2. Placez toujours le stop loss indiqué, dès l'entrée.
3. Une entrée manquée est une entrée manquée : ne poursuivez pas le prix.
4. Respect et entraide. Pas de publicité, pas de spam.

**VOS OUTILS**
Setup Analyzer, Journal de trading, Calendrier économique, Bubble Map et Calculateur de pips, gratuits pour commencer :
→ https://www.leterminal.net

__Le trading comporte un risque de perte en capital. Les signaux publiés ici sont partagés à titre éducatif et ne constituent pas un conseil en investissement. Ne tradez que ce que vous pouvez vous permettre de perdre.__
```

---

## 2. Nouveau signal

Visuel : `signal.png` (ou générateur, état Signal : sens, actif, entrée, TP1, TP2, TP3 et SL sur l'image). Vous pouvez ajouter une capture du graphique en second média.

```
**NOUVEAU SIGNAL — [XAUUSD]**

[▲ ACHAT] · [H1]

Entrée : `[2 345,50]`
TP1 : `[2 352,00]`
TP2 : `[2 358,50]`
TP3 : `[2 368,00]`
SL : `[2 340,50]`

Risque : `[50]` pips · R:R jusqu'à `[1:4,5]`

**Le contexte** : [une ou deux phrases — structure, zone, déclencheur].

Risquez 1 % maximum. Stop placé dès l'entrée.
```

> Pour une vente, remplacez `▲ ACHAT` par `▼ VENTE`.

---

## 3. TP1 atteint

Visuel : `tp1.png` (ou générateur, état TP1). En réponse au signal.

```
**TP1 ATTEINT — [XAUUSD]**

✓ Premier objectif encaissé : `[+65]` pips (`[+1,3 R]`).

Stop déplacé au point d'entrée : le risque est retiré du trade. La suite se joue sans pression.
```

---

## 4. Stop au point d'entrée

Visuel : `be.png` (ou générateur, état BE). En réponse au signal, juste après TP1.

```
**STOP AU POINT D'ENTRÉE — [XAUUSD]**

Déplacez votre stop loss à `[2 345,50]`.

Le trade ne peut plus être perdant. Laissez courir vers TP2 et TP3.
```

---

## 5. TP2 atteint

Visuel : `tp2.png` (ou générateur, état TP2). En réponse au signal.

```
**TP2 ATTEINT — [XAUUSD]**

✓ Deuxième objectif encaissé : `[+130]` pips (`[+2,6 R]`).

Le plan se déroule. La position restante court vers TP3, stop toujours au point d'entrée.
```

---

## 6. TP3 atteint, trade clôturé

Visuel : `tp3.png` (ou générateur, état TP3). En réponse au signal.

```
**TP3 ATTEINT — [XAUUSD]**

✓ Objectif final atteint : `[+225]` pips (`[+4,5 R]`).

Trade clôturé en totalité. Le plan a été exécuté de l'entrée à la sortie.

Notez ce trade dans votre journal pour garder la trace de ce qui fonctionne :
→ https://www.leterminal.net/journal
```

---

## 7. Stop loss touché

Visuel : `sl.png` (ou générateur, état SL). En réponse au signal.

```
**SL TOUCHÉ — [XAUUSD]**

✕ Stop loss touché : `[−50]` pips (`[−1 R]`).

Perte limitée, conforme au plan : le risque était défini avant l'entrée. Une perte maîtrisée fait partie de la méthode.

On passe au trade suivant.
```

> Si TP1 avait déjà été atteint et le stop déplacé au point d'entrée, publiez plutôt ce post, avec le visuel `be-sortie.png` (ou générateur, état Sortie BE) :
>
> ```
> **SORTIE AU POINT D'ENTRÉE — [XAUUSD]**
>
> Le prix est revenu sur l'entrée après TP1 : la position restante est sortie à `0` pip.
>
> Bilan du trade : `[+65]` pips encaissés sur TP1, aucun risque pris sur le reste.
> ```

---

## 8. Les outils du Terminal

Une fois par semaine au maximum. Mettez en avant **un seul** outil par post, en tournant : Setup Analyzer, Journal, Calendrier économique, Bubble Map, Calculateur de pips.

```
**AVANT VOTRE PROCHAIN TRADE**

Faites analyser votre graphique par le Setup Analyzer : structure, zones clés et un verdict clair (GO, ATTENDRE ou NO-GO) en quelques secondes.

Envoyez une capture, obtenez une seconde lecture avant de cliquer.

→ https://www.leterminal.net/app

Gratuit pour commencer, sans carte bancaire.
```

---

## 9. Nouvel article du blog

Joignez la bannière de l'article (`/blog/img/[slug].webp`).

```
**NOUVEL ARTICLE — [TITRE DE L'ARTICLE]**

[Une phrase qui pose le problème que l'article résout.]

Au programme :
— [point 1]
— [point 2]
— [point 3]

→ https://www.leterminal.net/blog/[slug]
```
