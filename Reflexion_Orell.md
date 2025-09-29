# Reflexion zur CI-Pipeline


Ich habe im Laufe dieser Prüfung eine GitHub Actions Pipeline erstellt, die insgesamt drei Jobs hat. Die Jobs werden noch unterteilt in spezielle Aufgaben. Es gibt drei Jobs: Der erste heißt "Lint". In diesem wird vor allem ein Linter ausgeführt. Dieser überprüft den Quellcode automatisch auf Fehler, unsauberen Stil und potenzielle Probleme wie vergessene Semikolons.

Es macht Sinn, zuerst den Code mit dem Linter zu prüfen, dann zu testen und anschließend zu deployen, da Code, der nicht den Guidelines entspricht, nicht deployed werden sollte.

Verbesserungen für die Zukunft wären eine genauere Auseinandersetzung damit, welche Teile der Pipeline wirklich benötigt werden und welche Resultate gespeichert werden sollten, etc.