# Behandlungsportal



Wir beschäftigen uns hier genauer mit der Dateneingabe und starten mit dem Klick auf das `+` - Symbol. Der Ereignis-Typ ist ein DropDown - Menü mit Auswahlwerten. Bespielhaft wählen wir jetzt einen `Mahlzeiten Bolus` aus, um Insulinmenge und KH hinzuzufügen.


**Ereignis-Typ:**

![nightscout_careportal](../images/nightscout/nightscout_careportal.jpg)


Die Auswahlfelder werden entsprechend der Auswahl angepasst.

Eingabe von KH und Insulineinheiten erfolgen jetzt. Wichtig ist auch noch die Eingabe der
korrekten **Zeit**, falls man Daten nicht online eingeben kann, da diese zusammen mit den CGM - Werten grafisch dargestellt werden.

In dieser Maske können wir auch temporäre Basalraten mit `Temp Basal Start/End` eingegeben. Diese werden anschließend grafisch dargestellt.
Nach dem Klick auf **Eingabe Senden** wird man noch aufgefordert, die eingaben zu bestätigen. Mit **OK** ist alles gespeichert.




Nun können wir uns  alles grafisch ansehen:

![nightscout_cp_entries](../images/nightscout/nightscout_cp_entries.jpg)



**Benachrichtigungen** über Therapie - Behandlungsdaten

Wenn Benachrichtigungen über Behandlungsdaten aktiviert sind, werden Benachrichtigungen generiert wenn eine Eingabe im Careportal gemacht wurde. Mögliche Alarmeinstellungen werden kurz danach unterdrückt. Die Standard - Unterdrückungsdauer beträgt 10 Minuten. Dieses kann über Azure App.-Einstellungen geändert werden, in dem man die TREATMENTNOTIFY_SNOOZE_MINS
Variable ändert.



Weiter gehts mit der  Verwendung des  [Bolus Rechner](../nightscout/boluscalculator.md).
