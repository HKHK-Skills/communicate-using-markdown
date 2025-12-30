<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Samm 1: Lisa pealkirjad

_Tere tulemast kursusele "Suhtlemine Markdown'i abil"! :wave:_

**Mis on _Markdown_?** Markdown on [kerge süntaks](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) GitHubis suhtlemiseks. Saad vormindada teksti, et lisada pealkirju, loendeid, **paksu**, _kaldkirja_, tabeleid ja palju muid stiile. Saad Markdown'i kasutada enamikus kohtades GitHubis:

- Kommentaarid [issue'des](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull request'ides](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) ja [aruteludes](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Failid laiendiga `.md` või `.markdown`
- Tekstilõikude jagamine [Gist'ides](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

**Mis on _pealkiri_?** Pealkiri on suurem tekst sektsiooni alguses. On kuus suurust.

### Näide

```md
# See on `<h1>` pealkiri, mis on suurim

## See on `<h2>` pealkiri

###### See on `<h6>` pealkiri, mis on väikseim
```

#### Kuidas see välja näeb

# See on `<h1>` pealkiri, mis on suurim

## See on `<h2>` pealkiri

###### See on `<h6>` pealkiri, mis on väikseim

### :keyboard: Tegevus: Muuda oma faili pealkirjadega

1. Ava uus brauseri vahekaart ja tööta sammude kallal teises vahekaardis, lugedes juhiseid sellel vahekaardil.
1. Ava **pull requests** vaheleht.
1. Kliki **New pull request**, harude võrdlemiseks vali `base: main` ja `compare: start-markdown`.
1. Kliki **Create pull request**.
1. Selles pull request'is mine vahekaardile **Files changed**. Tegime sulle tühja faili `index.md`.
1. Vali **Edit file** kolme punktiga **...** menüüst failivaate üleval paremal nurgal failil `index.md`.
1. Vahekaardil **Edit file** lisa `#`, millele järgneb **tühik**, enne ükskõik millist sisu, mida soovid, et muuta see H1 pealkirjaks. Saad lisada rohkem pealkirju, kasutades ühte kuni kuut `#` märki, millele järgneb **tühik**.
1. Uue sisu kohal kliki **Preview**.
1. Lehe allosas kirjuta lühike, tähenduslik commit-sõnum, mis kirjeldab failis tehtud muudatust.
1. Kliki **Commit changes**.
1. Oota umbes 20 sekundit ja seejärel värskenda seda lehte (seda, kus sa juhiseid loed). [GitHub Actions](https://docs.github.com/en/actions) uuendab automaatselt järgmise sammu juurde.
