# final-roommate-finder

Step 1: Summarizing the tasks of the app.

O aplicaţie web/mobile prin intermediul căreia oamenii vor putea găsi colegi de apartament şi locuinţe de închiriat.

Utilizatori = cei ce s-au înregistrat pe site
Vizitatori  = cei ce vizionează site-ul fără să fie logaţi/înregistraţi

Există mai multe tipuri de utilizatori:
	->(Ofertant) cei ce vor să închirieze unul sau mai multe apartamente.(diferenţiaţi: Agenţie/Proprietar)
	->(Coleg cu apt.) cei ce au o locuinţă şi îşi caută coleg de apartament
	->(Coleg) cei ce nu au o locuinţă şi îşi caută coleg de apartament

La înregistrarea în site, noul utilizator va fii întrebat care din cele 3 tipuri de utilizator este(va avea posibilitatea să schimbe pe viitor)

Există 2 formulare diferite: 
	-> Formular_Ofertant:
		-nume
		-prenume
		-adresa_email
		-poza_profil
		-apartamente_de_închiriat [standarde stricte; se acceptă doar apartamente curate, şi igienizate]
			-locatie(adresa exacta + coordonate google_maps)
			-etaj
			-nr_camere
			-compartimentare
			-este_mobilat
			-pret_lunar
			-nr_maxim_colegi
			*
			-anunţ_activ
			-nr_reporturi
			*
	-> Formular_Coleg:
		-nume
		-prenume
		-adresă_email
		-poză_profil
		-dată_naştere
		-sex
		-ocupaţie
		-descriere_personală
		-oraş
		-zona_oraş(are posibilitatea de a alege: irelevant,una sau mai multe zone)
		-este_fumător
		-are_animal_companie
		-nivel_curăţenie
		-nivel_musafiri
		-vizibil_pentru_vizitatori
		*
		-profil_activ
		-nr_reporturi
		*

Odată înregistraţi, utilizatorii dispun de următoarele funcţionalităţi:
	->editarea profilului personal sau a anunţurilor
	->aplicarea filtrelor de căutare pentru colegi/apartamente
	->contactarea prin chat a altor utilizatori
	->plasarea steguleţelor de report în dreptul profilelor/apartamentelor ce nu respectă 'normele bunului-simţ'
	->schimbarea vizibilităţii profilului/apartamentului
	->butonul de 'batem-palma' din chatbox va dezactiva automat vizibilitatea anunţului/profilului
	->'by default' anunţurile/profilurile vor fi setate pe invizibil la 48h de la ultima logare, vizibilitatea profilelor resetându-se prin apăsarea butonului "Da" într-un pop-up ce apare odată cu relogarea utilizatorului: "Au trecut 48h de la ultima Dumneavoastră logare, mai sunt valabile anunţurile x,y,z?" =>'da,nu,da'.

	
Spaţiu restrâns pentru reclame.
