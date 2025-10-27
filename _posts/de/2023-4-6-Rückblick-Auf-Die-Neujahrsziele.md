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
  - Deutsch
  - Ziele
  - Neues Jahr
---

Es sind ein paar Monate vergangen, seit ich hier ein Update zu den beruflichen und programmierbezogenen Zielen gegeben habe, die ich mir für das neue Jahr gesetzt hatte.

Mein übergeordnetes Ziel für das Jahr war es, *jeden* Tag zu programmieren. Das ist ein ziemlich großes Ziel – und das Leben kann manchmal schnell dazwischenkommen und perfekte Serien unterbrechen. Auch wenn ich dieses Ziel vielleicht nicht vollständig erreicht habe, programmiere ich an den meisten Tagen. Oft ist es besser, auf Fortschritt und Wachstum hinzuarbeiten, statt auf *Perfektion*.

#### Neujahrsziele

Zur kurzen Erinnerung – das waren die drei weiteren Ziele, die ich mir gesetzt hatte:

1. Eine persönliche Blog-Seite erstellen  
2. Eine verbesserte Version meiner Lebenslauf-Webseite entwickeln, inklusive Hell- und Dunkelmodus  
3. Die Zertifizierungen „Azure Data Fundamentals“ und „Azure AI Fundamentals“ erwerben  

#### Eine persönliche Blog-Seite erstellen

Wenn du diesen Beitrag liest, habe ich eine persönliche Blog-Seite erstellt!

Es gibt unendlich viele Möglichkeiten, wenn man einen persönlichen Blog aufbaut – angefangen bei Programmiersprachen, über Hosting-Plattformen bis hin zu zusätzlichen Tools. Schon früh im Entwicklungsprozess habe ich entschieden, dass ich meinen Blog mit einem Static Site Generator erstellen und über GitHub Pages hosten möchte.

Man könnte sich fragen, warum ich mich für einen Static-Site-Generator entschieden habe. Ich habe nichts gegen dynamische Webseiten, aber mir gefällt, wie schnell statische Seiten laden und wie wenig laufende Wartung sie benötigen. Meine [persönliche Webseite](https://michelle-heatherly.com) hoste ich bereits über GitHub Pages. Mit der einfachen und kostenlosen Hosting-Option für statische Webseiten war die Wahl des Hostings schnell getroffen.

Manchmal ist es einfach schön, die Dinge *einfach* zu halten.

Ich habe einige verschiedene Bibliotheken ausprobiert, um mir den Einstieg in die Erstellung einer statischen Blog-Seite auf GitHub Pages zu erleichtern.

Die folgenden Bibliotheken beschreibe ich im Detail weiter unten:

1. [Jekyll](https://jekyllrb.com/)  
2. [Jekyll Now](https://github.com/barryclark/jekyll-now)  
3. [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)  

##### Jekyll

Jekyll ist ein Open-Source-Tool, das auf der Programmiersprache Ruby basiert und mit HTML- und Markdown-Dateien arbeitet. Es eignet sich hervorragend zur Erstellung statischer Webseiten, was bedeutet, dass die Dateien als vorgerenderte HTML-Dateien ohne dynamisch generierte Inhalte oder zusätzliche Back-End-Dienste & Datenbanken bereitgestellt werden.  
Einige Vorteile von Jekyll sind die vollständige (und **kostenlose**) Integration mit GitHub Pages, sowie die Tatsache, dass Jekyll-Webseiten oft schneller, sicherer und leichter zu warten sind als Content-Management-Systeme (CMS).

##### Jekyll Now

[Jekyll Now](https://www.jekyllnow.com/), entwickelt von Barry Clark, ermöglicht es Entwickler*innen, ihre Jekyll-Webseite in wenigen Minuten zum Laufen zu bringen, ohne Ruby und andere Abhängigkeiten installieren zu müssen.

Wie der Name schon andeutet, kann man damit sehr schnell eine neue statische Blog-Seite erstellen. Das mitgelieferte Design ist minimalistisch, schlicht und schön, sodass man seine Energie auf das Schreiben von Blogbeiträgen und Inhalten konzentrieren kann.

Mein Testlauf mit einem Fork des Jekyll-Now-Repositories ist [hier](https://michelle-heatherly.com/jekyll-now/) zu finden.

##### Minimal Mistakes

Nachdem ich mit Jekyll Now experimentiert hatte – und obwohl mir die Einfachheit gefiel – wollte ich eine Bibliothek verwenden, die mehr Funktionen direkt integriert. Nach einiger Recherche stieß ich auf [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), ein flexibles, responsives und anpassbares Jekyll-Theme, das von Michael Rose entwickelt wurde.

Im Gegensatz zu Jekyll Now erfordert dieses Theme, dass Ruby installiert und konfiguriert ist, sowie die Nutzung von Ruby Gems für Installation und Bundling des Themes.

Ruby war auf meinem Computer bereits von früheren Projekten installiert. Wer es noch nicht hat, findet auf der [Ruby-Webseite](https://www.ruby-lang.org/en/documentation/installation/) mehrere Möglichkeiten zur Installation auf verschiedenen Betriebssystemen. Die Dokumentation zum Einstieg und zur Konfiguration von Minimal Mistakes ist ebenfalls sehr umfangreich.

Ich liebe, wie anpassbar und erweiterbar dieses Theme ist und wie es gleichzeitig hilft, den Erstellungsprozess zu beschleunigen. Für [diesen](https://michelle-heatherly.com/blog/) Blog, den du gerade liest, habe ich Minimal Mistakes verwendet.

Wie viele persönliche Programmierprojekte ist auch dieser Blog noch eine laufende Arbeit. Wahrscheinlich werde ich weiterhin andere Tools erkunden, um meine Blog-Webseiten weiterzuentwickeln. Einige der Tools, die mich künftig interessieren, sind [Hugo](https://gohugo.io/) und [11ty](https://www.11ty.dev/).

#### Persönliche Webseite mit Hell- und Dunkelmodus verbessern

In den letzten Monaten habe ich viele Updates an meiner persönlichen Webseite vorgenommen.

Einige der Änderungen sind:

1. Farbverlauf-Text für die Navigationsleiste, Überschriften und andere Stellen zur zusätzlichen Betonung.  
2. Einige Bilder wurden durch aktuellere Screenshots ersetzt oder solche, die besser zum Gesamtdesign der Webseite passen.  
3. Das Video wurde durch einen Farbverlaufs-Hintergrund mit dynamischer, animierter Textdarstellung des Grace-Hopper-Zitats ersetzt.  
4. Den Karten im Portfolio-Bereich wurden Badges hinzugefügt, die anzeigen, welche Sprachen und Tools bei der Entwicklung verwendet wurden.  

Allerdings habe ich bisher keinen Hell- und Dunkelmodus zu meiner persönlichen Webseite hinzugefügt.

Es gibt ein bekanntes Sprichwort im kreativen Schreiben (ich glaube, es wird William Faulkner zugeschrieben), das besagt, man solle seine „*Lieblinge töten*“. Das heißt, man sollte sich nicht zu sehr an etwas klammern. Manchmal ist es besser, liebgewonnene kreative Werke zu überarbeiten oder loszulassen.

Ich genieße das dunkle, cyber/galaxy-inspirierte Design meiner Webseite derzeit sehr. Ich stimme aber zu, dass es sinnvoll sein könnte, irgendwann eine Webseite zu erstellen, die über eine Hell-/Dunkelmodus-Umschaltung verfügt, um meine Fähigkeiten als Softwareentwicklerin klarer und professioneller zu präsentieren. Ich bin mir nur noch nicht sicher, wie ein neues Design aussehen soll.

Ich experimentiere bereits mit einigen neuen Layouts und Technologien, mit denen die Webseite entwickelt wird. Vermutlich wird im Laufe des Jahres ein neues Design entstehen, das meinen Vorstellungen entspricht. Bleibt dran!

Allerdings habe ich für andere Projekte Hell-/Dunkelmodi entwickelt.

Zum Beispiel:

Ich habe dieser [Jekyll-Blog-Seite](https://michelle-heatherly.com/blog/) einen Umschalter für Hell-/Dunkelmodus hinzugefügt. Du kannst zwischen den Modi wechseln, indem du auf das Sonne-/Mond-Symbol in der Navigationsleiste klickst. Das Standard-Theme ist dunkel (bzw. das „neon skin“ von Minimal Mistakes), da es zum *ästhetischen* Stil meiner [Webseite](https://michelle-heatherly.com) passt.

Außerdem habe ich ein kleines Beispielprojekt mit Angular, TypeScript und Angular Material erstellt, bei dem man ebenfalls zwischen Hell- und Dunkelmodus wechseln kann. Eine Vorschau findest du [hier](https://michelle-heatherly.com/angular-material-color-toggle/).  
Der Code für alle diese Projekte ist auf meiner [GitHub](https://github.com/michelleheatherly)-Seite einsehbar.

Erwähnenswert ist auch, dass die aktuelle (Alpha-)Version von [Bootstrap 5](https://getbootstrap.com/docs/5.3/customize/color-modes/#dark-mode) eine integrierte Funktion für Hell-/Dunkelmodus bietet. Man muss zwar weiterhin einen Button hinzufügen und etwas zusätzlichen Code schreiben, um zwischen den Themes zu wechseln, aber es ist eine großartige Option, wenn man Bootstrap ohnehin bereits verwendet.

#### Azure Data Fundamentals und Azure AI Fundamentals Zertifizierungen erwerben

Seit Ende Februar 2023 besitze ich drei Azure-Zertifizierungen: Azure Fundamentals, Azure Data Fundamentals und Azure AI Fundamentals.

Wer sich für Azure-Zertifizierungen interessiert, kann regelmäßig an [virtuellen Trainingstagen](https://www.microsoft.com/en-us/trainingdays) von Microsoft teilnehmen. Einige dieser Trainings, darunter Azure Fundamentals, Data Fundamentals und AI Fundamentals, beinhalten sogar kostenlose Prüfungsgutscheine. Diese Grundlagenzertifizierungen sind ideal für alle, die neu im Cloud-Computing oder in Azure sind und ihr Wissen erweitern und validieren möchten.

Auch wenn du bereits Erfahrung mit Azure oder anderen Cloud-Plattformen wie AWS oder GCP hast, sind diese Trainings eine gute Möglichkeit, neue Dienste und Features kennenzulernen. Ich kann nur empfehlen, das **kostenlose** Training und die Gutscheine zu nutzen, wenn du mehr über Azure und seine Möglichkeiten erfahren möchtest.  
Zur Prüfungsvorbereitung habe ich außerdem [Microsoft Learn for Azure](https://learn.microsoft.com/en-us/training/azure/) verwendet – eine **kostenlose** Lernplattform mit hervorragenden Lernmaterialien, Übungen und kurzen Tests, um dein Wissen zu prüfen oder neue Fähigkeiten zu erlernen.

Da man aktuell kaum an OpenAI und ChatGPT vorbeikommt, hat mich das Lernen für die Azure-AI-Fundamentals-Prüfung sehr inspiriert, tiefer in die Themen Künstliche Intelligenz und Maschinelles Lernen einzutauchen. Die Prüfung behandelt Themen wie die KI-/ML-Dienste auf Azure, Natural Language Processing, Computer Vision und auch ethische Fragen und Verantwortlichkeiten im Umgang mit KI/ML.

Da viele Unternehmen zunehmend KI-Technologien integrieren oder eigene Lösungen entwickeln, steigt die Nachfrage nach Wissen und Fachkenntnissen in diesem Bereich. Auch wenn diese Zertifizierung nur eine grundlegende ist, empfand ich das Lernmaterial als großartige Einführung in die Nutzung von Azure-Diensten für KI/ML.

Zwei interessante KI-Tools, die ich kürzlich entdeckt habe, sind:

1. [sudowrite](https://www.sudowrite.com/)  
2. [Writesonic](https://writesonic.com/)  

##### sudowrite

Sudowrite ist eine Anwendung, die KI/ML nutzt, um Autor*innen kreativ zu unterstützen. Einige der Funktionen sind Vorschläge für alternative Wörter oder Sätze, Charakterentwicklung, Brainstorming, das Generieren von Gedichten und vieles mehr. Besonders spannend finde ich den „Canvas Mode“.

##### Writesonic

Writesonic ist eine weitere KI-gestützte Schreibanwendung, die beim Erstellen von Texten hilft – sei es für Blogbeiträge, Beschreibungen, das Umformulieren von Absätzen, Ideengenerierung, Keywords und vieles mehr. Außerdem gibt es eine neue Funktion namens *Photosonic*, mit der man Kunst generieren kann.

Beide Tools bieten eine **kostenlose** Testversion an. Probiert sie ruhig aus! Wie bei vielen anderen KI-/ML-Tools variieren die Ergebnisse stark. Es braucht oft etwas Feingefühl und Experimentieren mit den Parametern, um die besten Resultate zu erzielen.

#### Nächste Schritte

Wie viele andere Entwickler*innen habe auch ich eine fortlaufende Liste mit Projekten und Ideen.

Kurzfristig möchte ich mich auf diese drei Dinge konzentrieren:

1. Eine Linktree-inspirierte Webseite erstellen  
2. Eine Blog-Webseite für meine Yoga-Angebote aufbauen  
3. Eine Full-Stack-CRUD-Anwendung entwickeln  

Danke fürs Lesen! Ich hoffe, dass diese Gedanken und Ressourcen dich bei deinen eigenen Programmierprojekten inspirieren.

Ich werde weiterhin an mir selbst arbeiten und bald ein weiteres Update zu meinem Fortschritt bei diesen drei Zielen geben.

Ich hoffe, deine eigenen Ziele laufen gut!