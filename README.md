# FCSC 2025 AES Distrace

Vous avez la possibilité d’exécuter ce binaire qui effectue un chiffrement AES-128-ECB sur une entrée aléatoire, tout en observant la valeur d’un registre à une adresse fixée tout au long du calcul.

**Note :** le chemin `/app/` dans le fichier Python fourni (`aes-distrace.py`) est à adapter à votre environnement pour faire tourne l’épreuve localement.

Auteur : Cryptanalyse

Origine : [AES Distrace](https://hackropole.fr/fr/challenges/crypto/fcsc2025-crypto-aes-distrace/)


## Challenge
[files/aes-distrace.c](files/aes-distrace.c)
[files/aes-distrace](files/aes-distrace)
[files/aes-distrace.py](files/aes-distrace.py)
[files/libexeclog.so](files/libexeclog.so)
[files/qemu-x86_64](files/qemu-x86_64)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-crypto-aes-distrace.git

> cd fcsc2025-crypto-aes-distrace

> docker compose up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/crypto/fcsc2025-crypto-aes-distrace/
