1. Hvað gera eftirfarandi Linux skipanir?
	*	cd - change directory
	*	cd ~ - fer á root
	*	ls - listar möppur í directoryinu sem þú ert í
	*	pwd - Sýnir hvar þú ert staddur
	*	mkdir - Býr til nýja möppu

2. Hvað gera eftirfarandi git skipanir og hvers vegna eru þær gagnlegar?
	*	git clone - clónar verkefni í tilvalna möppu, hún er gagnleg til að clóna verkefni til þín ef þú vild vinna í því
	*	git log	- Sýnir öll commitin, Ef þú vild vita hvenar þú commitaðir síðast
	*	git status - sýnr stöðuna á tréinu sem þú ert að vinna á, Ef þú vild vita stöðuna
	*	git diff - sýnir mun á commits,files eða trjám, Hún er gagnleg þegar þú vilt bera saman eitthvað tvennt
	*	git checkout - til að skipta um grein, hún er gagnleg þegar þú vilt fara af master greininni eða á hana

3. Hver er munurinn á eftirfarandi git skipunum:
	*	a) git diff - gerir ekkert(Fann allaveganna ekkert um það)
	*	b) git diff --staged - sýnir munin á fyrra commit og files sem eru núna staged
	*	c) git diff commit1 commit2 - sýnir munin á milli þessara tveggja commits

4. 	Hvað er útgáfustýring (e.version control)? Forrit sem heldur utan um allar breytingar sem hafa verið gerðar á verkefninu sem þú ert að vinna í. Forritið skrifar niður breytinganar og skrifar hvenær hún var gerð og hver gerði hana.

5.	Hverjir eru helstu kostir við að nota GIT? Það er kostur við það að GIT heldur um allar breytingar sem þú hefur gert í verkefninu, Það geta fleirri en einn unnið á sama verkefninu á sama tíma, Þú getur gert grein sem hefur enga áhrifa á aðal forritið ef breytingin gekk ekki upp.

6.	Hversu oft telur þú að eigi að gera commit í verkefni, rökstuddu? Ef þú gerir einhverja villu í framtíðinni og veist ekki hvernig á að laga hana þá getur þú bara fraið til baka þegar forritið virkaði eðlilega

7.	Hvað er "Working directory"?" "Staging area"?" og "Repository" í GIT?
	* Working directory - Er svæðið sem þú vinnur í verkefninu sem þú tókst af Repository
	* Staging area - Er mappa sem heldur utan um hvað fer í þínu næsta commit
	* Repository - Er geymslan sem heldur utan um verkefnið

8.	Hvenær er sniðugt að nota greinar (branches)? Þegar þú ætlar að prufa að gera einhverja breytingu sem þu ert ekki alveg viss um svo að þú skemmir ekki aðal verkefnið eða ætlar að halda áfram með verkefnið öðruvísi en langar ekki að breyta aðal verkefninu