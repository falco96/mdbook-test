# Comandi principali

## 1. Accedere al root

>
	su

oppure

>
	sudo -i

Nel primo caso inserire la password di root, nel secondo la password del proprio utente

## 2. Aggiornare il sistema

Per aggiornare il sistema

>
	dnf upgrade -

In alcuni casi

>
	dnf update

Dopo l'aggiornamento del sisstema è sempre consigliabile riavviare

>
	reboot

## 3. Installare, cercare e rimuovere un programma

**Per installare un programma:**

>
	dnf install nome programma

**Per rimuovere un programma:**

>
	dnf remove nome programma

**Per cercare un programma**

>
	dnf search nome programma

## 4. Gestione file e cartelle

**Per creare una cartella**

>
	mkdir nome cartella

**Per creare directory dentro ad altre directory**

>
	mkdir -p /dir1/dir2/

**Creare un file di testo**

>
	nano ciao.txt

*Questo comando può essere utiizzato per creare numerose tipologie di file. Si consiglia **nano** e non un altro editor in quanto nano è il più semplice*

