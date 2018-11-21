## Lisitr'ireo commandes base ilaina amin'ny linux

 *Rehefa voavakinao tsara ilay lesona premier pas dia mitohy ihany ianao... * :smiley:

1- Hanombohantsika an'azy aloha dia sokafy ny teminal satria eo isika no hianatra 
tsindrio ny "ctrl+alt+t" dia ahita zavatra maintimainty feno soratsoratra kely mitovy amin'ilay film fijerinao 
ireny ianao.Tena ireny tokoa ve ny fampiasana ny terminal?
___
Andao jerentsika miandalana izay : 
___

1- Raha tianao ho fantatra hoe aiza ao anatin'ilay pc ny misy anao dia tapeo eo amin'ilay terminal ity : 

    **pwd**  : raha adika lavalava kokoa dia (print name of current working directory ) 

2- Ankoatra izay raha tianao fantarina ny mahakasika ny PC anao dia tsindrio ny 

    *uname -a* na ihany koa *name --all* 
Dia ho hitanao eo ny mombamomba ilay PC anao.

##Mbola liana ve ianao? Mbola te hanohy sa leo sahady?

*Tsara ny mampahafantatra anao aloha fa ny commande rehetra izay ampiasainao dia afaka ampiarahinao amin'ny 
**--help** na **man + commande** dia hahita ny fomba fampiasana azy hianao*
___
3- Andeha isika hianatra hi-creer fichier.

*Misy fomba maromaro ahafahana micreer fichier amin'ny linux fa ny aingana indrindra dia*

    touch + nom_de_fichier.extension ohatra => touch index.md
    
*Tsara kokoa rehefa manana fichier ianao dia classena anaty dossier iray foana izany andeha isika hianatra 
hicreer dossier , tsy dia sarotra akory*

    mkdir nom_du_dossier ohatra => mkdir lesona2
    
*Rehefa izay dia hiditra ao anatin'ilay dossier isika , ny fidirana ao dia manahirana NON je blague fa*

    cd nom_du_dossier izany hoe => cd lesona2
    
*Afaka jerentsika avokoa ny zavatra ao amin'ny alalan'ny mots magique*

    ls  , aza gaga raha tsy misy n'inon'inona fa dossier vide anie no no-creentsika teo.
    
*Mba hampisy zavatra ao dia ho afindrantsika ao ilay fichier no-creentsika teo aloha noho izany dia tsy maintsy miala ao aloha isika
tsy voatery miala akory fa jerentsika indray izay fomba iray izay rehefa ao aoriana kely ao fa izao aloha mandeha tsikelikely*

    cd ..
    
*Hitanao fa tafavoaka tao ianao* :smile: , *Raha eo isika no mijery ny liste , **ls** dia hitantsika eo ilay fichier nataontsika tany aloha
ho afindrantsika anatin'ilay dossier izy*

    mv nom_du_fichier dossier/ izany hoe => mv index.md lesona2/
    
*Raha miverina manao **ls** ianao dia tsy eo intsony ilay fichier*, *Tsy very akory ilay izy fa efa nafindrantsika
anatin'ilay dossier lesona2*

*Midira ao amin'ilay lesona2 dia jereo izay zavatra ao fa tokony ho hitanao ao ilay fichier sady mianatra ianao eto*

*Nahatsikaritra ianao fa mitovy amin'ny **couper** na **cut** ilay commande notapentsika teo*. *Dia ahoana izany ny copie?*

    cp  nom_f_1 nom_f_2  izany hoe => cp index.md index2.md 

*Dia hitanao fa nahazo fichier 2 samihafa ianao, koa satria mbola fichier 1 ihany no ilaintsika dia ho fafantsika
ilay fichier iray copie*

    rm nom_f_a_effacer izany hoe => rm index2.md
    
*Afaka miverina manao listing ianao fa tsy hitanao ao intsony ilay fichier 2 , ahoana kosa indray raha dossier no fafana na hafindra sy copiena?*

    1- mv dossier1 dossier2 => raha hamindra
    2- cp -r dossier1 dossier2 => raha hanao copie
    3- rmdir nom_d_dossier  => raha hamafa
    
*Fanamarihana mahakasika ny cd fa misy racourci izy io. Misy racourci avokoa ny commande fa ny cd aloha no
ampahafantariko anao anio*

    - cd ~ (raha te hoany amin'ny répértoire de base anao any )
    - cd / (raha te hoany amin'ny fototr'ilay system ianao ) :yum: fa zao , tandremo rehefa tonga ao mamafa zavatra fa hein :sunglasses:
    - cd - raha te ho ao amin'ilay répértoire teo aloha ianao :innocent: 


*Izay ny anio aloha fa misaotra anao namaky , raha fintinina dia ireto avy ny zavatra tokony efa hainao ny dikany*

    pwd, ls, uname, cd, cp, mv, mkdir, rmdir, touch, rm.
    
*Anjaranao ny mijery ny fanalavana azy ireo fa efa ireo ny fampiasana azy sady fikarohana hoanao koa izany* 

**Tohizantsika amin'ny resaka permission sy utilisateur ny amin'ny manaraka** :grin: 




