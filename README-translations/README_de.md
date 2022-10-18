# Erste Beiträge

| <img alt="RStudio" src="../assets/rstudio-logo.png" width="300"> | RStudio Edition |
| ---------------------------------------------------------------- | --------------- |

Dieses Repo ist eine zerstückelte, abgespeckte und für RStudio angepasste Version des Erstaunlichen [Erste Beiträge](https://github.com/firstcontributions/first-contributions) Repository (und ist nicht offiziell mit RStudio verbunden). Sehen Sie sich das Original-Repo an, um Anweisungen zur Verwendung anderer Tools und Sprachübersetzungen zu erhalten.

## Einleitung

Es ist schwer. Es ist immer schwer, wenn man etwas zum ersten Mal macht. Besonders bei der Zusammenarbeit ist es nicht angenehm, Fehler zu machen. Aber bei Open Source dreht sich alles um Zusammenarbeit und Zusammenarbeit. Wir wollten die Art und Weise vereinfachen, wie neue Open-Source-Mitwirkende lernen und zum ersten Mal beitragen.

Das Lesen von Artikeln und das Ansehen von Tutorials kann helfen, aber was gibt es Besseres, als die Dinge tatsächlich zu tun, ohne etwas durcheinander zu bringen. Dieses Projekt zielt darauf ab, eine Anleitung zu geben und die Art und Weise zu vereinfachen, wie Anfänger ihren ersten Beitrag leisten. Denken Sie daran, je entspannter Sie sind, desto besser lernen Sie. Wenn Sie Ihren ersten Beitrag leisten möchten, folgen Sie einfach den einfachen Schritten unten. Wir versprechen Ihnen, es wird Spaß machen.


## Was dies Sie lehren wird

- wie man ein Repository forkt
- Wie man einen Zweig macht
- So senden Sie eine Pull-Anforderung an das ursprüngliche Repository

## Was dir das nicht beibringen wird

- So erstellen Sie R-Pakete
- Open-Source-Etikette

## Annahmen

Beim Schreiben dieses Leitfadens habe ich eine Reihe von Annahmen getroffen:

- Sie haben ein GitHub-Konto
- Sie haben RStudio installiert [RStudio](https://www.rstudio.com/products/rstudio/download/#download) installed.
- ['Happy Git und GitHub für den Benutzer'](http://happygitwithr.com/)


## Forken Sie dieses Repository

Forken Sie dieses Repo, indem Sie auf die Fork-Schaltfläche oben auf dieser Seite klicken.

<img width="300" src="../assets/fork.png" alt="fork this repository" style = "display: inline;"  />
<br/>

Dadurch wird eine Kopie dieses Repositorys in Ihrem Konto erstellt und Sie werden zu dieser Version des Repositorys weitergeleitet.

Sie müssen jetzt die URL für Ihr Repo abrufen. Klicken Sie auf „ Klonen oder herunterladen“ und kopieren Sie die URL in das Feld.

<img width="300" src="../assets/rstudio-gh-clone.png" alt="clone the repo" style = "display: inline;"  />
<br/>

## Erstellen Sie ein neues Projekt

Gehen Sie in RStudio zu Datei -> Neues Projekt

Wählen Sie „ Versionskontrolle“ und dann „ Git“.

Fügen Sie im Dialogfeld „Neues Projekt“ die URL, die Sie von GitHub kopiert haben, in das Feld „ Repository-URL“ ein.

Wählen Sie den gewünschten Namen für das Verzeichnis auf Ihrem Computer und geben Sie ihn in das Feld "Name des Projektverzeichnisses" ein. Standardmäßig ist dies der Name des Repos.

Wählen Sie abschließend aus, wo das geklonte Repo gespeichert werden soll, indem Sie auf die Schaltfläche „Durchsuchen“ klicken.

Wenn Sie fertig sind, klicken Sie auf „Create Project“, um das Repo zu klonen und das Projekt einzurichten.

<img width="300" src="../assets/rstudio-clone.png" alt="Git"  style = "display: inline;"  />
<br/>

Das Repo wird nun in den von Ihnen angegebenen Ordner geklont.

## Erstellen Sie einen Zweig

Klicken Sie auf der Registerkarte „Git“ oben rechts auf die Schaltfläche „Neuer Zweig“.

<img width="500" src="../assets/git-tab-location.jpg" alt="Git tab"  style = "display: inline;"  />
<br/>
<img width="300" src="../assets/rstudio-new-branch-button.png" alt="Create a new branch"  style = "display: inline;"  />
<br/>

Benennen Sie Ihren Branch "add-your-name", zum Beispiel: "add-nic-crane".

<img width="300" src="../assets/rstudio-new-branch-button2.png" alt="name your branch"  style = "display: inline;"  />
<br/>

Stellen Sie sicher, dass „Zweig mit Remote synchronisieren“ aktiviert ist und klicken Sie auf „Erstellen“. Möglicherweise werden Sie aufgefordert, Ihren GitHub-Benutzernamen und Ihr Passwort einzugeben.


## Nehmen Sie notwendige Änderungen vor und übernehmen Sie diese Änderungen

Öffnen Sie nun die Datei „Contributors.md“ in RStudio, fügen Sie Ihren Namen hinzu und speichern Sie die Datei.

Sie werden sehen, dass neben der Datei ein „M“ steht. Aktivieren Sie das Kontrollkästchen daneben und klicken Sie dann auf „Commit“.

<img width="300" src="../assets/rstudio-add.png" alt="name your branch"   style = "display: inline;"  />
<br/>

Sie sehen eine Diff-Datei mit den Änderungen, die Sie an der Datei vorgenommen haben. Fügen Sie eine Commit-Nachricht hinzu – eine Zusammenfassung der von Ihnen vorgenommenen Änderungen – und klicken Sie dann auf „Commit“. Ein Kästchen erscheint, um die Übergabe zu bestätigen; klicken Sie auf "Schließen".


## Pushen Sie Änderungen an GitHub

Herzlichen Glückwunsch, Sie haben alle Änderungen an Ihrer lokalen Kopie Ihres Zweigs Ihres Fork of first-contributions festgeschrieben. Klicken Sie nun auf „Push“, um Ihren Commit mit dem Remote-Repo zu synchronisieren.

<img width="400" src="../assets/rstudio-commit-message.png" alt="name your branch"   style = "display: inline;"  />
<br/>

Sie sehen ein Kästchen wie dieses, wenn Ihre Änderungen erfolgreich übertragen wurden. Klicken Sie auf „Schließen“.

<img width="400" src="../assets/rstudio-push2.png" alt="name your branch"   style = "display: inline;"  />
<br/>


## Reichen Sie Ihre Änderungen zur Überprüfung ein

Wenn Sie auf Github zu Ihrem Repository gehen, sehen Sie die Schaltfläche „Compare & Pull Request“. Klicken Sie auf diese Schaltfläche.

<img width="500"  style = "display: inline;" src="../assets/compare-and-pull.png" alt="create a pull request"   />
<br/>

Stellen Sie sicher, dass Sie Gabeln vergleichen. Links sollte der Master-Branch des ursprünglichen Repos sein, und rechts sollte der neue Branch sein, den Sie in Ihrem Repo erstellt haben. Nachdem Sie die richtigen Optionen ausgewählt und eine kurze Zusammenfassung der vorgenommenen Änderungen geschrieben haben, senden Sie die Pull-Anforderung, indem Sie auf „Pull-Anforderung erstellen“ klicken.

<img width="500" style = "display: inline;" src="../assets/submit-pull-request.png" alt="submit pull request"   />
<br/>

Bald werde ich alle Ihre Änderungen in den Master-Zweig dieses Projekts zusammenführen. Sie erhalten eine Benachrichtigungs-E-Mail, sobald die Änderungen zusammengeführt wurden!

Glückwunsch! Sie haben gerade den Standard-Workflow _fork -> clone -> edit -> PR_ abgeschlossen, dem Sie als Mitwirkender oft begegnen werden!

























