

# Andao isika hanampy utilisateur iray anatin'ny pc anao

Aleo zandrikely = lita mba ampidirintsika ao koa :smiley: tsy zandrikely le eritretin'ny gasy io a ! , *ndao ary!!!*

Rehefa mampiditra utilisateur dia misy command `useradd` ny add dia midika fa ampio+ izany hoe ampio an'ilay user manaraka eto command iray ligne dia ahafahanao manampy utilisateur.

1- `useradd lita` 
izay dia vita :smiley: ny commande de base iaingana aloha *useradd [options] identifiant*

Rehefa mipetraka ilay utilisateur dia afaka ampianao mots de passe izy ,satria mety misy zavatra perso ao :wink: , toy ny teo aloha dia commande iray koa dia vita izany `passwd user` izany hoe :

2- `passwd lita`

Amin'ny sehatra hafa dia be dia be ny utilisateur gerenao , izany hoe mila atambatambatra anatin'ny groupe samy hafa izy ireo ahafahana manamora ny gestion an'izy ireny  :grin: , ny famoronanana group dia toy ilay namorona user ihany `groupadd groupe-name` , inona moa ilay add nolazaina teny ambony ?

3 - `groupadd anaran_ilay_group`

Rehefa manana ilay groupe ianao dia azonao atao ny mampiditra utilisateur ao, fanamarihana , ny sudo ihany koa dia group :hushed: 

Ny fampidirana utilisateur dia `gpasswd -a user group` izany hoe :

4- `gpasswd -a lita anaran_ilay_group`

Raha te hanala utilisateur anatin'ilay groupe ianao dia soloinao fotsiny ilay option `-a` teo aloha ho `-d` izay midika delete. *Matetika ny -a midika hoe manampy ny -d mamafa raha option ! * izany hoe :

5- `gpasswd -d lita anaran_ilay_group`

Raha ohatra ka hanala ny access an'ilay utilisateur ianao dia ny mifanohitra amin'ilay `useradd` no soratanao izany hoe `userdel` ny del izay midika ho mamafa `userdel [option] user` toy izao :

6- `userdel -r lita`

Amin'ny manaraka indray.


