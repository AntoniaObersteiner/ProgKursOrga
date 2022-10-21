Artemis

12022-09-30
ProgKursTreff: Eric hat sich für Artemis angeboten
-> Übungen und Tests sammeln

12022-10-01
Treffen mit Morgenstern und Eric vorgeschlagen
	https://dud-poll.inf.tu-dresden.de/progkursartemis/

produktiv schon von DDI verwendet
	PCpool, accounts automatisch erstellen, mit Schnipseln ausgeteilt
	Morgenstern + Domanowski arbeiten an Shibboleth
	4 VM-Agents
	mit Endlosschleifen und anderen Fehlern kann leicht Überlastung auftreten

Basics erstmal nur mit print-statements
	Artemis dann für etwas komplexere Aufgaben

Übertragen von Aufgaben
	im Ziel einen neuen leeren Kurs erstellen
	dann force pushen oder mergen aus bestehenden Repos

Kursen „Artemis per git“ optional ans Herz legen; see below

Erstmal einen Artemis-Kurs für alle Programmierkurse, 
	dann je nach Interesse Aufgaben verwenden

damit template immer bei 0% beginnt, können tests auch 0 Pkt geben

unsere instructor-accounts: ewolf und aobersteiner
	bedeuten automatisch gitlab-ownership
	andere rollen
		editor (nur bearbeiten, nicht erstellen)
		tutor (nicht bearbeiten, kann lösung sehen)
		student (keine lösung (außer irgendwann veröffentlicht))

aktuell können studis die Kurse nicht sehen

git repos unter kurse -> edit -> choose exercise (runter scrollen)
	auch als ssh, dann einstellen

studis
	einschreiben/Register
	dann im overview öffnen -> editor / clonen 

für erstis nicht natives PyTest-assert verwenden! 
	fail mit deaktiviertem trace is besser (mit functools standardmäßig deaktivieren)
	notfalls mit if bzw. match arbeiten

Morgenstern im Matrix?
	Accounts für Studis -> Anzahl, dann generiert 

PC-Pools: turtle sollte dabei sein, matplotlib vorher anfragen
interner docker wird hoffentlich von Ubuntu 20.04 auf 22 aktualisiert
	-> Py 3.10 statt 3.8
