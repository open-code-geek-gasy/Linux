# Ny système de fichiers

Tsy dia tena resaka théorie an'ny **système de fichiers** izy ity fa ny organisation misy @ système GNU/Linux fotsiny aloha.

Alefa !! :penguin:

## Fampahafanarana kely na izany aza

Ny **système de fichiers** na **file system** (ataontsika hoe FS manomboka eto) dia ny fomba fandaminana ny fichiers sy repertories ao anaty support (cd na dvd na disque dur na usbdisk sy ny sisa).
_Fandaminana ahoana moa izany ?_ Io izany no mamaritra hoe aiza ho aiza ao anatin'io support io ilay fichier na ilay repertoire, io no mamaritra hoe iza no repertoire parent ary aiza ho aiza ao anaty arborescence ilay fichier na repertoire iray :worried: ... 

Efa haintsika fa miendrika arboresence ny fipiriman'ny fichiers. Ohatra hoe ao anaty disque misy repertoire **BON** dia avy eo misy sous repertoire **CODES** dia ao anatin'io misy fichier hoe **test.cpp**, ary dia ohatr'izany hatrany. Ka ny FS dia _index_ kely ao anaty support iray mandamina an'izay arborescence izay. _Mety mazavazaka kely kosa amin'izay e ?_

Tohizana ary ... io FS io (io _index_ kely io) dia misy isaky ny support SY isaky ny partition ary mety ho samihafa ny firafiny (format-ny izany na ny structure-ny mety foana izay fomba ahazahoanareo azy). Ireo karazany ireo le henonareo isan'andro ireny hoe FAT, VFAT, NTFS, HPFS, sns. Aty amin'ny tontolon'ny GNU/Linux dia mahare isika ny EXT2, EXT3, EXT4, ReiserFS, sns. Maro tsy tambo isaina ireo ary samy manana ny mahaizy azy ka tsy mbola eto amin'ity pejy ity no hanaovantsika fampitahana momba izany, tadidio fotsiny fa raha Ubuntu ohatra no ampiasaina dia EXT4 no FS par défaut ao.

Averina kely, isaky ny support SY isaky ny partition iray dia misy FS. Raha ampitahaina dia isaky ny mahita io FS io ohatra ny système d'exploitation Microsoft Windows dia manisy _**racine**_ iray : C:\ na D:\ na E:\ na F:\. Ny GNU/Linux kosa dia _**racine**_ iray ihany na firy na firy isan'ny FS hitany ao, "**/**" io _**racine**_ io.

Raha iverenantsika ilay ohatra tetsy ambony, ny _chemin_ na _path_ ho an'ilay fichier **test.cpp** izany dia **/BON/CODES/test.cpp**

## Ny File hierarchy stadard

:pick:

## Ny chemin absolu sy relatif

:pick:

## Fivezivezena ao anaty arborescence

:pick:

_Nosoratana ny volana novambra 2018 (aleo asiana daty satria mety misy zavatra tsy mitombina intsony ireo afaka volana maromaro ohatra)_