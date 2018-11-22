#Ny ligne de commandes

Iverenantsika kely ary ny ligne de commandes na interpreteur de commandes amin'ny ankapobeny. Rehefa manao commandes ianao, ohatra hoe **pwd** dia mahazo valiny eo ambany eo. Ny tena marina dia nanome baiko ny interpreteur de commandes ianao hoe "aiza ho aiza eo amin'ny arborescence-ny systèmes de fichiers no misy ahy izao" na koe hoe "ao anaty repertoire inona aho izao".

_Sarotra ve ?_  Io re ilay antsoina hoe **_SHELL_** e !

Ny fiasan'ireo **shell** ireo no hojerentsika.

##Ahoana moa izany ?

Rehefa mampiasa commandes iny ianao, eo amin'ny terminal izany dia toy izao ny endrikendriny :

**prompt$commande [option(s)] [argument(s)]**

Toy izao avokoa ny fomba fanoratra amin'ny ankapobeny ny commandes rehetra amin'ny terminal. Hazavaina tsirairay ireo

##Ny shell aloha

Araky ny voalaza etsy ambony dia izy no manatanteraka ny baikonao. Maro isan-karazany anefa ny **shell** ary arakaraky ny distribution ampiasainao dia samy manana ny **shell** par défaut. Ireto kosa no fahitantsika matetika :
- bourne shell (/bin/sh)
- bourne shell again (/bin/bash)

Samy manana ny mahaizy azy anefa ireo shell rehetra misy (dash, ksh, zsh, tcsh, rbash, sns.) fa na izany aza ny **fototra** mitovy foana.

###Ny "prompt"

Manana endrika isan-karazany izy io ary azonao configurer-na amin'izay itiavanao azy (mba tsy hampifangaro voraka ity _tuto_ ity dia jerentsika amin'ny manaraka izay fanovana ny endriky ny _prompt_ izay, miaraka amin'ny _variables d'environnement_ angamba).

Raha ny machine ampiasaiko ato izao dia toy izao ny fisehony

**niry@niry:~$**

Raha hazavaina tsirairay ireo dia 

**nom d'utilisateur@nom du poste:repertoire courant$**

Izany hoe  :
- nom d'utilisateur : niry
- nom du poste : niry
- repertoire courant : ~ (midika hoe repertoire personnel io symbole io eto)

Amin'ny ankapobeny (sy par défaut) io caractère farany io dia na **$** na **#** (amin'ny ankapobeny hoy aho fa azo ovaina arak'izay itiavana azy koa io). Ny fanao mahazavtra dia :
- ny **$** manambara fa utilisateur tsotra no hanao _commande_ eo amin'io _shell_ io
- ny **#** manambara fa ny super utilisateur (ny faratampon'n utilisateurs rehetra) no hanao commande eo amin'ny _shell_

Ao aoriana kely no hijerentsika amin'ny antsipirihiny izay resaka utilisateur izay fa eto dia tadidio fotsiny hoe misy karazany roa izany izy ireo, misy utilisateur tsotra misy super utilisateur.

Ny commande dia aorian'ny _prompt_ no asiana azy. Tsy ianao no mi-taper ny _prompt_ fa rehefa eo izy dia manambara izay fa miandry ny commande-nao ny _shell_. Raha mbola tsy misy prompt izany eo fa zavatra hafa, ohatra hoe

** login: **

dia tsy mbola afaka mampiditra commande ianao satria tsy mbola misy shell afaka hi-interpreter ny commande-nao akory eo.

Noho izany, raha mahita commande amin'ny Internet ianao ka manaraka izany dia izay aorian'ny prompt ihany re no taper-na.

Farany, ireto commandes ireto no ahalalanao hoe inona no shell ampiasainao (ataovy fotsiny aloha fa rehefa miresaka variables isika hazava bebe kokoa)

**echo $0** na **echo $SHELL**

###Ny commande

Ny endiky ny commande dia efa hitantsika [tato](https://github.com/open-code-geek-gasy/Linux/blob/master/commande-base.md) fa ireto misy fanazavana fanampiny :
- ny commande dia manavaka **casse** izany hoe tsy mitovy ny **pwd** sy ny **Pwd** ary ny **PWD**. Rehefa minuscule dia minuscule, ny majuscule dia majuscule fa tsy azo afamadibadika
- ny commande dia afaka mandeha amin'izao (tsy misy option tsy misy arguments), ohatra hoe **ls**
- afaka misy option iray na maromaro **[option(s)]**, ohatra hoe **ls -l** na **ls -i -l** na **ls -ial** sns
- afaka misy argument iray na maromaro **[argument(s)]**, ohatra hoe **ls /dev**
- afaka sady misy option no misy argument, ohatra hoe **ls -l /dev**
- ny _espace_ dia TENA MISY DIKANY, io izany **commande _ espace _ [options(s)] _ espace _ [argument(s)]**, izay ilay commande ka raha **ls -al /dev** no tiana atao dia tsy mety io raha ataona **ls-al /dev** na **ls -a a / dev**

Reefa tianao ho fantatra ny mombamomba ilay commande (ny fampiasana azy ny options sy ny argunments) dia afaka mampaisa ny commande **man** ianao na **commande --help**

**man nom_de_commande** (Ohatra izany hoe **man ls**)

**ls --help**

##Efa mitady ho grand :smile:

Raha nahavita namaky hatreto ianao dia arahabaina fa kely sisa dia **grand** :punch: satria nahoana ? rehefa avy mi-taper _commande_ izany dia mba afaka mamaky izay soratany eo :
- raha miteny izy hoe misy olana ny commande (_command not found_ na _commande introuvable_) dia mba efa mahatakatra izany hoe misy olana kely eo amin'ilay commande, na diso tsipelina ilay izy na lasa misy majuscule na ohatr'izany
- raha option no resahiny (_invalid option_ na _option invalide_) dia mba hamarinina hoe inona no voasoratra eo amin'ny _option_
- raha argument no resahiny (_no such file or directory_) ohatra dia izay izany, tsy misy ilay argument resahinao

Dia izay indray aloha ...

_Nosoratana ny volana novambra 2018 (aleo asiana daty satria mety misy zavatra tsy mitombina intsony ireo afaka volana maromaro ohatra)_




