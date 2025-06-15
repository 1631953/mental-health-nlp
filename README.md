# Classificació de Trastorns Mentals i Detecció de Patrons Lingüístics en Xarxes Socials
Aquest repositori conté el codi i els resultats del Treball de Final de Grau _Classificació de Trastorns Mentals i Detecció de Patrons Lingüístics en Xarxes Socials_, centrat en l’ús de tècniques de processament del llenguatge natural (NLP) per detectar patrons lingüístics associats a diversos trastorns mentals en textos publicats a xarxes socials.

S’hi comparen diferents tècniques de representació del llenguatge —des de models clàssics fins a *Large Language Models* (LLMs)— combinades amb diversos classificadors. També s’avalua la seva capacitat per generalitzar en contextos clínics, com el corpus DAIC-WOZ.

## Estructura del repositori
```text
mental-health-nlp/
├── notebooks/           # 5 notebooks del projecte (1, 2 i 3 de Kaggle, 4 i 5 de DAIC-WOZ, amb resultats ocults)
├── results/
│   ├── figures/         # Visualitzacions t-SNE obtingudes
│   ├── lda_html/        # Visualitzacions LDA en format HTML
│   └── models/          # Millors models entrenats, vectoritzadors i label encoders (.joblib, .json)
├── .gitignore           # Fitxers i carpetes que Git ha d’ignorar
├── LICENSE.txt          # Llicència d’ús (CC BY-NC 4.0)
├── README.md            # Descripció del projecte
└── requirements.txt     # Dependències Python per executar els notebooks

````

> **Nota**: les dades utilitzades són de caràcter sensible o amb restriccions d’ús, per tant no s’inclouen directament en aquest repositori.


## Dades

- **Kaggle** — El conjunt de dades de Kaggle utilitzat es pot descarregar aquí:  
  [Sentiment Analysis for Mental Health – Kaggle Dataset](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health)

- **DAIC-WOZ** — Per motius de sensibilitat, les dades derivades del corpus clínic DAIC-WOZ no s'inclouen al repositori. Cal sol·licitar-les als autors i acceptar el seu acord d’ús:
  [DAIC-WOZ Database & Extended DAIC Database](https://dcapswoz.ict.usc.edu/) 

## Requisits

Aquest projecte està desenvolupat amb **Python 3.10**. Pots instal·lar els paquets necessaris amb:

```bash
pip install -r requirements.txt
