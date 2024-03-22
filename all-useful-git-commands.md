<table class="t1" data-cellspacing="0" data-cellpadding="0">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td class="td1" data-valign="top"><p><span class="s1">git
status</span></p></td>
<td class="td2" data-valign="top"><p><span class="s1">Gibt Info darüber
wieder, was an dem File verändert wurde</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git add -A<span
class="Apple-converted-space"> </span></span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Gibt alle
Veränderungen in die Staging Area</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git commit -m
„Made the header orange and removed a line oft ext“</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">So werden die
Veränderungen in die git History übernommen mit der Message was genau
passiert ist -m</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git checkout -- .
(Abstand zw - und .)</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Macht die
Vorgängerversion vom letzten Commit wieder zugängig, z.B: wenn
unabsichtlich was gelöscht oder ALLES gelöscht</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git push origin
master (=this is called PUSH)</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">lädt mein Project
auf Github hoch bzw. die Veränderungen meines Projects</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git pull origin
master (=this is called PULL)</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">lädt Veränderungen
vom Server runter zurück auf meine Files;<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git
--version</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">zeigt die Version
von Git an</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git config
--global user.name “MYNAME”</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">damit Git meine
Daten hat</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git config
--global user.email “christiane.paukner@gmx.at”</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1"> </span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">cd
/Users/Path/To/Directory</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">change directory
zu dem Folder den ich bearbeiten will</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">mkdir
„hello-world“</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">macht einen neuen
Folder im pwd</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git init<span
class="Apple-converted-space"> </span></span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Repo festlegen für
Git</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">touch
„index.html“</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">erstellt ein neues
html file namens Index im current directory</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git add
index.html</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">gibt alle
Veränderungen des files index.html in die Staging area<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">zuerst mit cd dort
hinnavigieren wo ich Repo haben will, dann:</span></p>
<p><span class="s2">git clone <a
href="https://github.com/LearnWebCode/welcome-to-git.git"><span
class="s3">https://github.com/LearnWebCode/welcome-to-git.git</span></a><span
class="Apple-converted-space"> </span></span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">wenn z.B: Website
besteht aber mein Kollege will, dass ich das runterlade und da
weitermache </span><span class="s4"></span><span class="s1"> damit ich
nicht alles von selber machen muss</span></p>
<p><span class="s1">Klont also quasi alles, was ich
brauche</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git remote set-url
origin <a href="https://github.com/MYUSERNAME/myname"><span
class="s3">https://github.com/MYUSERNAME/myname</span></a>oftherepo.git</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">git ändert URL,
die es fpr das Pushen und pullen von Änderungen vom origin repository
verwendet</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git remote
-v</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Liste der
konfigurierten Remote-Repositories wird zurückgegeben, die für mein
lokales Repo konfiguriert sind (für jedes Remote-Repo werden 2 Zeilen
angezeigt: eine für Fetch und eine für Push</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">pdftotext -layout
infile.pdf outfile.txt</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">konvertiert PDF zu
txt File; zuerst muss poppler-utils via apt oder conda installiert
werden</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">pandoc infile.html
--from html --to markdown_strict -o outfile.md</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">konvertiert HTML
zu md File; zuerst muss pandoc via conda installiert
werden</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git
branch</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">zeigt an den
current branch</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git checkout -b
NEWBRANCHNAME</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">wechselt zu neuem
Branch (original branch wird oben trotzdem noch
angezeigt)</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git checkout
BRANCH</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">wechselt zu
anderem, bereits exisitierendem Branch ohne dass ein neuer erzeugt
wird</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git merge
ZIELBRANCH</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">tut alles von
current branch übernehmen in den branch den ich will<span
class="Apple-converted-space"> </span></span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git
clone</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">klont das
Remote-Repository local von Github</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git
log</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">listet die
Commits</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git log
--oneline</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">alles schön in
einer Zeile zusammengefasst</span></p></td>
</tr>
<tr class="odd">
<td class="td3" data-valign="top"><p><span class="s1">git
revert</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">rückgängigmachen
von Commit (aber in History übernommen)</span></p></td>
</tr>
<tr class="even">
<td class="td3" data-valign="top"><p><span class="s1">git reset --hard
origin/main</span></p></td>
<td class="td4" data-valign="top"><p><span class="s1">Veränderungen im
working directory werden rückgängig gemacht</span></p></td>
</tr>
</tbody>
</table>
