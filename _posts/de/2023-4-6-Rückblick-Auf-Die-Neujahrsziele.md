---
layout: single
title: Rückblick auf die Neujahrsziele
lang: de
locale: de
header:
  image: /assets/images/laptop-and-coffee.jpg
categories:
  - Programmierung
tags:
  - Ziele
  - Neues Jahr
---

Es ist einige Monate her, seit ich hier ein Update zu den beruflichen und programmierbezogenen Zielen gegeben habe, die ich mir für das neue Jahr gesetzt hatte.

Mein übergeordnetes Ziel war es, *jeden* Tag zu programmieren. Das ist natürlich sehr ambitioniert – und manchmal kommt das Leben dazwischen und unterbricht perfekte Serien. Auch wenn ich dieses Ziel vielleicht nicht vollständig erreicht habe, programmiere ich an den meisten Tagen. Oft ist es sinnvoller, auf Fortschritt und persönliches Wachstum hinzuarbeiten als auf *Perfektion*.

#### Neujahrsziele

Zur Erinnerung – das waren meine drei weiteren Ziele für dieses Jahr:

1. Eine persönliche Blog-Seite erstellen  
2. Eine überarbeitete Version meiner Lebenslauf-Website entwickeln, inklusive Hell- und Dunkelmodus
3. Die Zertifizierungen "Azure Data Fundamentals" und "Azure AI Fundamentals" erwerben

#### Eine persönliche Blog-Seite erstellen

Wenn du diesen Beitrag liest, dann habe ich dieses Ziel bereits erreicht!

Es gibt unzählige Möglichkeiten, einen persönlichen Blog zu erstellen – von der Wahl der Programmiersprache über die Hosting-Plattform bis hin zu zusätzlichen Tools. Relativ früh im Prozess habe ich mich entschieden, meinen Blog mit einem Generator für statische Webseiten zu erstellen und über GitHub Pages zu hosten.

Warum ein Generator für statische Webseiten? Ich habe nichts gegen dynamische Websites, aber ich schätze, wie schnell statische Seiten laden und wie wenig Wartung sie erfordern. Meine [persönliche Website](https://michelle-heatherly.com) hoste ich ebenfalls über GitHub Pages – dank der unkomplizierten, kostenlosen Hosting-Möglichkeit war die Entscheidung naheliegend.

Manchmal ist es einfach gut, die Dinge *einfach* zu halten.

Ich habe verschiedene Bibliotheken ausprobiert, um den Einstieg in die Erstellung eines statischen Blogs auf GitHub Pages zu erleichtern.

Die folgenden Tools habe ich im Laufe der Entwicklung getestet:

1. [Jekyll](https://jekyllrb.com/)  
2. [Jekyll Now](https://github.com/barryclark/jekyll-now)  
3. [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)  

##### Jekyll

Jekyll ist ein Open-Source-Tool auf Basis der Programmiersprache Ruby, das mit HTML- und Markdown-Dateien arbeitet. Es eignet sich hervorragend zum Erstellen statischer Websites – also Seiten, die als vorgerenderte HTML-Dateien ohne dynamische Inhalte oder Backend-Systeme ausgeliefert werden.
Einige Vorteile von Jekyll: Es lässt sich vollständig und **kostenlose** mit GitHub Pages integrieren, und Jekyll-Seiten laden schnell, sind sicher und erfordern kaum Wartung – im Gegensatz zu klassischen Content-Management-Systemen (CMS).

##### Jekyll Now

[Jekyll Now](https://www.jekyllnow.com/) wurde von Barry Clark entwickelt und ermöglicht es, eine Jekyll-Seite in wenigen Minuten online zu bringen – ohne Ruby oder andere Abhängigkeiten installieren zu müssen.

Wie der Name schon andeutet, kann man damit sofort loslegen. Das mitgelieferte Design ist minimalistisch, aufgeräumt und schön – ideal, um sich ganz auf das Schreiben der Inhalte zu konzentrieren.

Meinen Testlauf mit einem Fork des Jekyll-Now-Repositories findest du [hier](https://michelle-heatherly.com/jekyll-now/).

##### Minimal Mistakes

Nach dem Experimentieren mit Jekyll Now – das mir durch seine Einfachheit gut gefallen hat – wollte ich ein Tool mit mehr integrierten Funktionen. Nach einiger Recherche stieß ich auf [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), ein flexibles, responsives und anpassbares Jekyll-Thema von Michael Rose.

Im Gegensatz zu Jekyll Now erfordert Minimal Mistakes die Installation und Konfiguration von Ruby sowie die Nutzung von Ruby Gems für Installation und Bundling.

Ruby war auf meinem Rechner bereits durch frühere Projekte installiert. Wer es noch nicht hat, findet auf der [offiziellen Ruby-Website](https://www.ruby-lang.org/en/documentation/installation/) gute Anleitungen für verschiedene Betriebssysteme. Auch die Dokumentation von Minimal Mistakes ist sehr umfangreich.

Ich liebe, wie anpassbar und funktional dieses Thema ist – und gleichzeitig den Entwicklungsprozess beschleunigt. Für [diesen Blog](https://michelle-heatherly.com/blog/de), den du gerade liest, verwende ich Minimal Mistakes.

Wie viele persönliche Programmierprojekte ist auch dieser Blog ein "Work in Progress". Wahrscheinlich werde ich künftig weitere Tools ausprobieren, um meine Blogseiten weiterzuentwickeln. Einige, die mich aktuell interessieren, sind [Hugo](https://gohugo.io/) und [11ty](https://www.11ty.dev/).

#### Persönliche Website: Hell- und Dunkelmodus

In den letzten Monaten habe ich viele Verbesserungen an meiner persönlichen Website vorgenommen.

Einige Beispiele:

1. Farbverlauf-Text in der Navigationsleiste, bei Überschriften und an anderen Stellen zur stärkeren Hervorhebung
2. Aktualisierte Screenshots, die besser zum Gesamtdesign passen 
3. Ein neues Hintergrundvideo mit Farbverlauf und animierter Textanzeige des Grace-Hopper-Zitats 
4. Neue Badges in den Projektkarten des Portfolios, die verwendete Sprachen und Tools anzeigen

Allerdings habe ich bisher noch keinen Hell-/Dunkelmodus eingebaut.

Es gibt ein bekanntes Zitat aus dem kreativen Schreiben – oft William Faulkner zugeschrieben – das besagt: "Kill your darlings." Gemeint ist, dass man sich nicht zu sehr an einzelne Ideen oder Designs klammern sollte. Manchmal ist es besser, sich von etwas zu lösen oder es zu überarbeiten.

Ich liebe das dunkle, vom Weltall inspirierte Design meiner aktuellen Website – trotzdem sehe ich den Nutzen eines Umschalters für Hell- und Dunkelmodus. Eine solche Funktion würde meine Fähigkeiten als Entwicklerin noch professioneller präsentieren. Ich bin mir nur noch nicht sicher, wie ein neues Design konkret aussehen soll.

Aktuell experimentiere ich mit neuen Layouts und Technologien. Ich gehe davon aus, dass im Laufe des Jahres eine neue Version meiner Website entsteht. Bleib also gespannt!

Für andere Projekte habe ich bereits Hell-/Dunkelmodi umgesetzt.

Zum Beispiel:

Auf meiner [Jekyll-Blog-Seite](https://michelle-heatherly.com/blog/de) gibt es eine Umschaltfunktion – klick einfach auf das Sonnen-/Mondsymbol in der Navigationsleiste. Standardmäßig ist der dunkle Modus aktiv (das sogenannte "Neon Skin" von Minimal Mistakes), weil es zum Design meiner [Website](https://michelle-heatherly.com) passt.

Ich habe auch ein kleines Beispielprojekt mit Angular, TypeScript und Angular Material erstellt, in dem man zwischen den Modi wechseln kann. Die Vorschau findest du [hier](https://michelle-heatherly.com/angular-material-color-toggle/).  
Den Code zu all diesen Projekten findest du auf meiner [GitHub-Seite](https://github.com/michelleheatherly).

Übrigens: Die aktuelle Alpha-Version von [Bootstrap 5](https://getbootstrap.com/docs/5.3/customize/color-modes/#dark-mode) bietet eine integrierte Hell-/Dunkelmodus-Funktion. Man muss zwar weiterhin einen Button einbauen und etwas Logik ergänzen, aber es ist eine großartige Option für alle, die bereits mit Bootstrap arbeiten.

#### Azure Data Fundamentals & Azure AI Fundamentals

Seit Ende Februar 2023 habe ich drei Azure-Zertifizierungen abgeschlossen: Azure Fundamentals, Azure Data Fundamentals und Azure AI Fundamentals.

Wenn du dich für Azure-Zertifizierungen interessierst, empfehle ich dir die regelmäßigen [virtuellen Trainingstage von Microsoft](https://www.microsoft.com/en-us/trainingdays). Einige davon – darunter Azure Fundamentals, Data Fundamentals und AI Fundamentals – beinhalten sogar kostenlose Prüfungsgutscheine.

Gerade für Einsteiger ins Cloud-Computing oder in Azure bieten diese Grundlagenzertifikate einen idealen Einstieg, um Wissen aufzubauen und zu validieren.

Auch wenn du bereits Erfahrung mit Azure, AWS oder GCP hast, kannst du durch diese Trainings neue Dienste und Features kennenlernen. Ich kann das **kostenlose** Lernangebot nur empfehlen.
Zur Vorbereitung habe ich zusätzlich [Microsoft Learn for Azure](https://learn.microsoft.com/en-us/training/azure/) genutzt – eine **kostenlose** Plattform mit großartigem Lernmaterial, Übungen und Quizfragen.

Besonders spannend fand ich die Vorbereitung auf die Azure AI Fundamentals-Prüfung, da das Thema Künstliche Intelligenz derzeit allgegenwärtig ist. Die Inhalte reichen von KI-/ML-Diensten in Azure über die Verarbeitung natürlicher Sprache und maschinelles Sehen bis hin zu ethischen Aspekten im Umgang mit KI.

Angesichts der steigenden Bedeutung von KI in der Industrie wird auch das entsprechende Fachwissen immer gefragter. Obwohl es sich nur um eine Grundlagenprüfung handelt, bietet sie einen ausgezeichneten Einstieg in Azure-basierte KI/ML-Anwendungen.

Zwei interessante KI-Tools, die ich kürzlich ausprobiert habe:

1. [sudowrite](https://www.sudowrite.com/)  
2. [Writesonic](https://writesonic.com/)  

##### sudowrite

Sudowrite unterstützt Autor*innen mit Hilfe von KI/ML – etwa beim Brainstorming, Umschreiben, Entwickeln von Figuren oder sogar beim Dichten. Besonders interessant finde ich den "Canvas Mode".

##### Writesonic

Writesonic ist ein weiteres KI-gestütztes Schreibtool, das beim Verfassen und Optimieren von Texten hilft – z. B. für Blogs, Produktbeschreibungen, Suchbegriffe und vieles mehr. Eine neue Funktion namens *Photosonic* ermöglicht zudem das Generieren von KI-Kunst.

Beide Tools bieten **kostenlose** Testversionen – probier sie ruhig mal aus! Wie bei vielen KI-Werkzeugen ist etwas Ausprobieren nötig, um wirklich gute Ergebnisse zu erzielen.

#### Nächste Schritte

Wie viele Entwickler*innen habe auch ich eine stetig wachsende Liste an Ideen und Projekten.

Kurzfristig möchte ich mich auf diese drei Vorhaben konzentrieren:

1. Eine Linktree-inspirierte Website erstellen
2. Eine Blog-Seite für mein Yoga-Angebot aufbauen
3. Eine Full-Stack-CRUD-Anwendung entwickeln

Danke fürs Lesen! Ich hoffe, dass dir diese Einblicke und Tools neue Impulse für deine eigenen Programmierprojekte geben.

Ich werde weiter an meinen Zielen arbeiten – ein weiteres Update folgt bald.

Ich hoffe, deine eigenen Projekte laufen ebenfalls gut!
