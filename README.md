# Beschreibung der Anwendung
Meine praktische Arbeit hat den kreativen Titel „Bachelorarbeit To-Do Liste“. Die Funktionalität dieser nützlichen Anwendung ist es eine To-Do Liste bereitzustellen. Da ich gerade parallel meine Bachelorarbeit schreibe kann ich diese benutzen, um mir offene Aufgaben zu merken und übersichtlich anzuzeigen. Ein Vorteil dieser innovativen Idee im Vergleich zu bestehenden Alternativen wie z.B. „Google Keep“ ist es, dass meine sehr wichtigen, offenen Aufgaben nicht an einen amerikanischen Großkonzern weitergegeben werden und kein Zugriff auf meine Standortdaten und Telefonbuch benötigt wird. Im Vergleich zu analogen Alternativen möchte ich hier den Umweltschutz hervorheben, da der Papierverbrauch um 100% reduziert wird. Außerdem befriedigt diese Anwendung das tiefe menschliche Urbedürfnis nach Listen und Elemente auf diesen abzuhaken.

Die Anwendung hat ein Eingabefeld in das die neue, zu bearbeitende Aufgabe eingegeben werden kann. Durch den Button „Hinzufügen“ wird diese an die Liste offener Aufgaben angehängt. Durch Ankreuzen der vorangestellten Checkbox kann die Aufgabe als abgeschlossen markiert werden. Mit einem Klick auf „Markierte entfernen“ werden alle abgehakten Aufgaben entfernt, um die Liste übersichtlich zu halten.

![alt text](https://github.com/AndreasZachariae/Webtechnologien/blob/master/list1.png?raw=true)
---
Die Herausforderung beim Programmieren war es beliebig lange Listen mit dazugehörigem HTML Code zu erstellen. Dies wurde durch Einfügen des Codes als Text in ein Array realisiert. Das Problem ist es aus diesem Array Elemente zu löschen ohne das Lücken entstehen über die nicht mehr iteriert werden kann. Durch das Löschen würde sich auch der Index verschieben und die Checkboxen könnten nicht mehr richtig zugeordnet werden. Deshalb wird ein einem separaten Array gespeichert welche Elemente noch nicht abgehakt sind und beim Aktualisieren werden nur diese Elemente angezeigt. 

![alt text](https://github.com/AndreasZachariae/Webtechnologien/blob/master/list2.png?raw=true)
---
![alt text](https://github.com/AndreasZachariae/Webtechnologien/blob/master/list3.png?raw=true)
