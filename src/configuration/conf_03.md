# Abilitare RPM Fusion Free e Non Free

Procedere con l'attivazione dei repo free e non free, per poter avere accesso a tutta una serie di software altrimenti non accessibili con i repository di default di Fedora. 

## RPM Fusion Free

Digitare i seguenti comandi da terminale

>
	su
	dnf install \
  	https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm

## RPM Fusion Non free

Da terminale digitale

>
	su
	dnf install \
  	https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

## Aggiornare i repository

Consiglio di aggiornare i repository facendo da terminale:

>
	dnf upgrade

## Riavviare il sistema

Non è obbligatorio, ma lo consiglio:

>
	reboot


