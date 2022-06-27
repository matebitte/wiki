# Bleiakkus

```HINWEIS: Momentan noch nicht ganz fertig!```

Ziel dieser Notiz ist ein kleines Schnellstarthandbuch zu schaffen, nicht allumfänglich zu sein. Auch habe ich keine elektrotechnische Ausbildung, sondern mir den kram übers internet angelesen, es ist also eher ein Erfahrungsbericht und keine geprüfte Anleitung. Links sind keine Belege sondern Klickempfehlungen. Der Einsatzzeck auf den ich mich beziehe ist das Betreiben von [[mobile-pa]] Anlagen.

<br/>

## Generelles
### Akku vs Generator
Bleiakkus können eine Alternative zu mobilen Generatoren für Veranstaltungen sein, sie allerdings je nach Dimension nicht immer ersetzen. Die Energiedichte von Diesel ist einfach sehr hoch und damit auch die andauernde Leistungsfähigkeit eines Notis. Für kleinere und mittlere Anforderungen (zB eine Anlage mit 600w Nennleistung für einige Stunden auf moderater Lautstärke) sind sie jedoch perfekt: es gibt keine Abgase oder nerviges Rattern im Lauti, sie sind Umweltfreundlich (Blei ist je nach Modell zu ca 90% recycelbar) und auch Problemlos auf einem Lastenrad zu Betreiben (kein Schmutz, keine heißen Teile oder Abgase).

**Heißt konkret:** Lesekreise, Podiumsdiskussionen, Fahrradlautis und kleine Bühnen sind sinnvolle Einsatzgebiete, ein 8h Rave eher nicht. Dafür ist eine höhere Energiedichte nötig und somit ein Generator oder andere Akkus vonnöten.

### Eigenschaften
Bei AGM Batterien ist die Säure in einer Art Schwamm (Glasvlies) gebunden – auch bei einer Beschädigung der Batterie kann keine Säure austreten und die Batterie kann in jeder Lage betrieben werden. Gleichzeitig stützt das Vlies die Platten gegeneinander ab und sorgt so für hohe Rüttelfestigkeit.
Durch Überladung frei gewordenes Wasser kann durch das Vlies immer wieder in die Batterie eingebunden werden, so dass die Leistungsfähigkeit erhalten bleibt. Bei langen Stillstandsphasen haben AGM-Batterien eine niedrige Selbstentladung. Auch bei niedrigen Temperaturen haben AGM-Batterien gute Eigenschaften. Damit sind sie ein guter Kompromiss, um sowohl kurzzeitig eine hohe Leistung zu erhalten und darüber hinaus auch eine lange Lebensdauer zu bieten. [[Vergleich von Batterietechnologien von BSAbatteries](http://www.bsabatteries.de/batterie_technologien.html)]

<br/>

## Beschaffung
Der Shop meines Vertrauens ist autobatterienbilliger.de. Die favorisierte Serie ist "Accurat T" (nicht T Pro!), je nach gewünschter Kapazität zB die [Accurat Traction T230 AGM Versorgungsbatterie](https://www.autobatterienbilliger.de/Accurat-Traction-T230-AGM-Versorgungsbatterie) (230Ah). Aber Vorsicht: auf das Gewicht achten! Ab 180Ah wird es Schwer. Mit einem 250Ah Akku sind für normale Menschen Rückenschmerzen Vorprogrammiert.

Dazu ist noch ein [Ladegerät](https://www.autobatterienbilliger.de/PACO-MEC1212-12A-12V-8-Stufen-Batterieladegeraet) und ein [Inverter](https://www.autobatterienbilliger.de/ECTIVE-SI-15-Sinus-Inverter) nötig. Zur Verbindung von Akku Terminal und Inverter werden dicke Kabel benötigt, und zwar aus Kupfer (kein billiges Alu-Gelumpe!). Stichworte sind hier Batteriekabel, Fahrzeugleitung und Scheißkabel. [[Gutes Guide zu Kabeln](https://www.youtube.com/watch?v=Mb0LQ19DEaI)

Die Verlinkten Sachen sind (zusammenpassende) Beispiele. Generell ist wichtig ist darauf zu achten, dass alles für 12v ausgelegt ist, die Maximalleistung vom Wechselrichter zum gewünschten Einsatzzeck passt und das Ladegerät auch zur Akkutechnologie passt. 

Eine größere Zusammenstellung an Links findest du bei [Thorbijoern](https://thorbijoern.github.io/wiki/#sourcing%2Fbuying%20batteries).

<br/>

## Benutzung

- immer schön die Schutzkappen auf die Terminals (Metalldingesi wo Strom anliegt)
- nicht beide Terminals anfassen (ist wie in die Steckdose fassen)
- generell nicht über 50% entladen
- nach dem Aufladen abstecken, nicht ewig am Ladegerät lassen!
- Trocken und Kühl Lagern, aber nicht unter 5 Grad. 
  - realistisch: nicht neben die Heizung legen, idealerweise auf dem Boden aber ohne Fuszbodenheizung)

### Betriebsdauer
Eine grobe Vorabrechnung wie lange ein Akku hält, lässt sich so berechnen: `Akkukapazität / benötigte Stromstärke = Betriebsdauer`
**Beispiel:** wir haben einen 205Ah Akku und wollen wissen wie lange wir damit unsere Anlage betreiben können. Die benötigte Stromstärke bekommen wir aus `Leistungsaufnahme in W /Betriebsspannung = benötigte Stromstärke`.
Gehen wir mal von einem Verbrauch von 400w auf 230v aus. Drauf kommen 20% Verlust durch das Invertieren von 12v auf 230v, wir Rechnen deshalb mit 480w: `480w/12v = 40A`. Das setzen wir jetzt zusammen mit der Akkukapazität in die Formel ein: `205Ah / 40A = 5.1h`. Weil wir den Akku aber nicht tiefentladen wollen, gehen wir eher von realen 3h aus.

Zu beachten ist die theoretische Maximalleistung der Verbraucher, die bei normaler Nutzung nie erreicht wird: kein Mensch ballert den Fahrradlauti auf voller Lautstärker durch die Gegend. Es klingt scheiße und ein Gehörschaden ist der fahrenden Person sicher. Je basslastiger die Musik ist, desto mehr Strom wird auch gezogen. Eine Podiumsdiskussion kann also also wesentlich länger versorgt werden als ein Techno act.

Gleichzeitig ist insbesondere bei Lautsprechern zu beachten, dass deren Leistungsaufnahme höher als die angegebene Leistung ist.

### Laden / Entladen
AGM Bleiakkus _können_ zwar mehr als 50% entladen werden, Vertragen das auch  halbwegs, aber es sollte vermieden werden. Überladen ist auch weniger ein Problem als bei Nassbatterien, aber sollte ebenfalls Vermieden werden.

Die Ladedauer lässt sich einfach Überschlagen: Kapazität Akku in Ah/Ausgabe Ladegerät in Ampere. --> 150Ah mit 12A aufzuladen wird so etwa 12 Stunden dauern (150Ah/12A = 12.5h)

<br/>

## Weiterführend
- [Thorbijoern's Wiki zu Akkus](https://thorbijoern.github.io/wiki/#accumulator%20-%20battery%20-%20rechargeable%20energy%20storage)
- [Thorbijoern's Wiki zu Invertern](https://thorbijoern.github.io/wiki/#inverter%20(Wechselrichter))
