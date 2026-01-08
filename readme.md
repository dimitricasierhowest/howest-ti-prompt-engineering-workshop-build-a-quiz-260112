# Workshop

Deze map bevat prompt-engineering oefeningen rond het periodiek systeem: voorbeelden van prompts, data en enkele single-file HTML demos.

Dit is bedoeld voor niet of minder technische gebruikers die willen kennismaken met prompt-engineering en AI-gegenereerde code. Om zelf apps te bouwen met AI.

## Inhoud

### html
- `workshop/app/index.html` startpagina met link naar de chemie demos.
- `workshop/app/chemie/index.html` overzicht van de HTML demo bestanden.
- `workshop/app/chemie/ds-quiz.html` flashcard/quiz app (namen en symbolen) in IMDb-stijl.
- `workshop/app/chemie/gem-quiz.html` quiz variant met IMDb-stijl UI.
- `workshop/app/chemie/gpt-quiz.html` uitgebreide flashcard/quiz variant.
- `workshop/app/chemie/gem-site.html` periodiek systeem in tabelvorm met zoekveld en detailweergave.

### prompts + data
- `workshop/prompts/01-data_prompt.md` prompt om data uit een afbeelding te halen en om te zetten naar MD/JSON.
- `workshop/prompts/02-quiz-prompt.md` prompt voor een SPA quiz/flashcard app.
- `workshop/prompts/03-table-prompt.md` prompt voor een SPA tabel van het periodiek systeem.
- `workshop/prompts/atomen.json` dataset met 118 elementen (atoomnummer, symbool, naam, categorie).
- `workshop/prompts/screenshot.png` en `workshop/prompts/tabel.png` referentiebeelden voor de prompts.

## Gebruik
1. Open `workshop/app/index.html` in chrome of een andere moderne browser.

## Netlify (account + drag and drop)
Voor statische sites (pure HTML/CSS/JS) kan je snel deployen met Netlify Drop.

1. Ga naar `https://app.netlify.com/signup` en log in met Google.
2. Ga naar "Add new project" > "Import an existing project" > "Try Netlify Drop".
3. Sleep je projectfolder naar de Drop-zone om te publiceren.

Voorbeeld: `https://melodic-bubblegum-e8e637.netlify.app/`
