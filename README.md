#Open Source

- Kolbrún Freyja Davidsen
- Perla Þrastardóttir

## 1. Linux uppsetning
Til að sækja Linux byrjuðum við á að fara inn á ubuntu.com.  Þar völdum við "download" og "desktop" og völdum 64 bita útgáfu af Ubuntu 12.04 LTS og náðum þar í .iso skrá. Því næst fórum við á slóðina http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-windows til að koma Ubuntu inn á USB kubb, til að við gætum bootað tölvuna og keyrt þannig Linux af USB.  
Af þessari síðu komumst við inn á "Pen Drive Linux's USB Installer".  Úr fellilista völdum við Ubuntu 13.10 Desktop amd64.  Svo þurftum við að finna .iso skránna og velja USB drifið og smella á "Create".  Við þurftum að staðfesta að valið drif væri USB lykillinn með því að smella á "Yes" og þá hófst niðurhölun inn á USB lykilinn. Á annarri tölvunni gekk allt eins og smurt en á hinni lentum við í klandri með að boota af lyklinum og þurftum við að reyna ítrekað.  Þegar því var lokið slökktum við á tölvunni og bootuðum með USB lyklinum.

Hér fyrir neðan eru myndir af tölvunum að boota upp á Linux:

![Mynd af tölvu Kolbrúnar](http://oi40.tinypic.com/oarwvp.jpg)
![Mynd af tölvu Perlu] (http://oi43.tinypic.com/2ahtn6g.jpg)

## 2. Uppsetning á vim && git

Til að setja upp vim og git fórum við eftir gefnum leiðbeiningum en þurftum reyndar að uppfæra Terminalinn fyrst og setja svo upp vim og git, hvort fyrir sig.  Þetta skref gekk vel, fyrir utan að við áttuðum okkur ekki á því alveg strax að við þyrftum að uppfæra en eftir að við áttuðum okkur á því gekk vel.

## 3. Unnið með Git (1. hluti)


Við stofnuðum báðar aðgang að Github og fórum eftir leiðbeiningunum til að forka skjalið. Við bjuggum til SSH-lykla sem reyndar gekk erfiðlega að koma inn í Github.  Við fórum eftir leiðbeiningum á síðu Github um hvernig eigi að búa til SSH-lykla en þegar kom að því að tengja lykilinn við Github með skipuninni: "sudo apt-get install xclip" fengum við villumeldinguna: E: Unable to locate package xclip.  Því urðum við að opna skránna í gedit og afrita þaðan inn á Github síðuna.  Eftir þetta fylgdum við leiðbeiningum og klónuðum verkefnið með git clone skipuninni. Þá gerðum við "cd INTOPrufa" og þaðan gátum við gert "vim NIM.cpp".  Þar fengum við upp kóðann fyrir leikinn og breyttum þar báðar kóðanum smávægilega.  Sú okkar sem var fyrri til gerði skipunina: "git push origin master", og þá þurfti hin að gera: "git pull" til að sækja breytingarnar.  Við sáum báðar okkar eigin breytingar þegar við fórum í Commit.  
Hins vegar sá Kolbrún ekki breytingar Perlu sama hvað við reyndum.  Við reyndum ítrekað að samræma breytingarnar en ekkert gekk.  Það var ekki fyrr en sólarhring seinna eftir miklar pælingar sem við áttuðum okkur á að sennilega er málið það að við forkuðum báðar skjalið og vorum þar af leiðandi sennilega að vinna hvor í sínu skjali.  
Þannig var að það gekk svo brösulega að ná Ubuntu yfir á USB lykil að við áttuðum okkur ekki á að því að aðeins önnur okkar átti að forka. Það var nefnilega þannig að í raun var alltaf bara önnur okkar inni á Ubuntu í einu vegna vandræða með USB-lykla og almennra vandkvæða með Ubuntu.  Að auki höfðum við ekki aðgang að dæmatímakennurum þessa viku sem var mjög slæmt í þessu tilfelli.  En við engu að síður gátum breytt kóðanum, gengið úr skugga um að þær breytingar sæjum við inni á Github - en að sjá breytingar hjá hvor annarri gátum við ekki.  Þegar við áttuðum okkur á því hvar vandamálið lá komumst við ekki inn á Ubuntu aftur, annar lykillinn fór í verkfall og á hinum var líka vesen.  Þannig að þó við hefðum áttað okkur á vandamálinu, gátum við ekki lagað það vegna vandkvæða með Ubuntu.  Það má alveg fylgja sögunni að við vorum að vinna í þessu á þriggja daga tímabili en ekki að grípa í þetta á síðustu stundu.   

Verkefnið okkar má finna á: https://github.com/kolbrunfreyja12/INTOPrufa.  Þennan hluta af verkefninu sjáum við báðar.
Breytingin sem Perla gerði er hér: https://github.com/perla11/INTOPrufa en þá breytingu sá Kolbrún ekki hjá sér af fyrrgreindum ástæðum.

## 4. Uppsettur hugbúnaður

Sá opni hugbúnaður sem við erum með á vélunum okkar er eftirfarandi:
<ul>
<li>Mozilla Firefox (Kolbrún og Perla)</li>
License: MPL 2.0.
Source code: https://github.com/mozilla/kuma

<li>Audacity (Perla)</li>

License: 	GNU General Public License.


Source code: http://audacity.sourceforge.net/download/source


<li>VLC Media Player (Kolbrún og Perla)</li>

License: GNU GPL v2.


Source code: http://www.videolan.org/vlc/download-sources.html

<li>QT creator (Kolbrún og Perla)</li>

License: GNU Lesser General Public License (LGPL).


Source code: https://qt.gitorious.org/qt-creator

<li>Code Blocks (Kolbrún og Perla)</li>

License: GPL v3.0.


Source code: http://www.codeblocks.org/downloads/25

<li>Ubuntu (Kolbrún og Perla)</li>

License:	Mainly the GNU GPL and various other free software licenses.


Source code: http://archive.ubuntu.com/
</ul>

## 5. Unnið með Git (2. hluti)

Að lokum forkuðum við Markdown skjalið og settum inn okkar texta við hvern lið með því að breyta README.md skjalinu. Í okkar tilfelli skrifuðum við eingöngu textann á sinn stað og settum nöfnin okkar í lista.  Þar sem við komumst ekki aftur inn á Ubuntu þurftum við að setja myndirnar beint í skjalið með sérstökum skipunum til að þær birtust í skjalinu.  
