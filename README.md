# Projet SAE2.1 : Mise en place d'un réseau d'entreprise fictif

Ce projet a été réalisé en équipe dans le cadre de la SAE2.1. L'objectif était de mettre en place le réseau d'une entreprise fictive qui déménageait. Ce répertoire contient des mémos de commandes pour diverses configurations réseau et services mais aussi le plan de ces deux jours de projet.

## Table des matières

1. [Introduction](#introduction)
2. [Prérequis](#prérequis)
3. [Installation](#installation)
4. [Utilisation](#utilisation)
5. [Mémentos de Commandes](#mémentos-de-commandes)
    - [DNS](#dns)
    - [NFS](#nfs)
    - [Plan de Réseau](#plan-de-réseau)
    - [ProFTPD](#proftpd)
    - [Samba](#samba)
    - [Webmail](#webmail)
6. [Auteur](#auteur)
7. [Remerciements](#remerciements)

## Introduction

Ce projet a pour but de simuler le déménagement et la reconfiguration du réseau d'une entreprise fictive. Le plan représente les étapes de déploiement de ce réseau. Les mémos de commandes fournissent des instructions détaillées pour configurer différents services réseau.

## Prérequis

- **Système d'exploitation** : Debian, Windows Server 2022, Windows 10
- **Accès root** ou capacité d'utiliser `sudo`
- **Matériels Physique** Routeur, Switchs, Cables, Clé bootable, ...

## Installation

Aucune installation spécifique n'est nécessaire pour utiliser les mémos ou bien de lire le plan.

## Utilisation

Chaque mémo de commande peut être utilisé indépendamment pour configurer les différents services sur votre réseau.

## Mémentos de Commandes

### DNS

Instructions pour configurer un serveur DNS sur Debian 10.

[Fichier DNS](Sae21/memento/dns.html)

### NFS

Instructions pour configurer un serveur NFS pour le partage de fichiers sur un réseau.

[Fichier NFS](/memento/nfs.html)

### Plan de Réseau

Le plan de réseau détaillant la topologie et les configurations nécessaires pour le déménagement de l'entreprise.

[Fichier Plan de Réseau](/memento/plan.html)

### ProFTPD

Instructions pour installer et configurer ProFTPD sur Debian 10.

[Fichier ProFTPD](/memento/proftpd.html)

### Samba

Instructions pour configurer un serveur Samba pour le partage de fichiers et l'intégration Windows/Linux.

[Fichier Samba](/memento/samba.html)

### Webmail

Instructions pour installer et configurer un serveur Webmail sur Debian.

[Fichier Webmail](/memento/webmail.html)

## Auteur

- **Votre Nom** - [lolosk](https://github.com/lolosk)


## Remerciements

Un grand merci à tous les membres de l'équipe pour leur travail et leur collaboration sur ce projet.
