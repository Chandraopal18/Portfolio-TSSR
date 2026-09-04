# Portfolio Réseau — TSSR

Bienvenue sur mon portfolio technique, réalisé dans le cadre de ma formation **TSSR (Technicien Systèmes et Réseaux)**.

Vous trouverez ci-dessous une sélection de projets réseau réalisés sur **Cisco Packet Tracer**, couvrant la segmentation VLAN, le routage (statique et dynamique), la traduction d'adresses (NAT), la haute disponibilité (agrégation de liens, redondance de passerelle) et la téléphonie IP.

Chaque projet dispose de sa propre fiche détaillée : contexte, objectifs, architecture, compétences mobilisées, difficultés rencontrées, ainsi que les fichiers de simulation (`.pkt`) et les configurations CLI complètes.

## 👤 À propos

**Chandra-Dev ARUMUGAM** — actuellement diplômé TSSR (Technicien Systèmes et Réseaux), je recherche une alternance en AIS (Administrateur d'Infrastructures Sécurisées) ou un poste de technicien systèmes et réseaux.

Passionné par l'infrastructure réseau, j'ai construit tout au long de ma formation une expertise pratique sur Cisco Packet Tracer : segmentation VLAN, routage statique et dynamique (OSPF), NAT, haute disponibilité (EtherChannel, HSRP) et téléphonie IP — que vous pouvez retrouver en détail dans les projets ci-dessous. Je m'intéresse particulièrement à la conception d'architectures réseau robustes et à la sécurisation des infrastructures.

Disponible pour une alternance à partir de 04/09/2026, je suis ouvert à toute opportunité me permettant d'allier théorie et mise en pratique concrète.

📧 [chandraopal18@gmail.com] · 🔗 [www.linkedin.com/in/chandra-dev-arumugam-61a6793b1]

## 🧰 Compétences couvertes dans ce portfolio

| Domaine | Projets concernés |
|---|---|
| Segmentation VLAN & Trunking 802.1Q | Tous les projets |
| Routage inter-VLAN (SVI, Router-on-a-Stick) | BigMac, OSPF, Agrégation & Redondance |
| Routage statique multi-sites | NAT, NAT statique / Port Forwarding |
| Routage dynamique OSPF multi-aires | OSPF |
| NAT dynamique (PAT / overload) | NAT, NAT statique / Port Forwarding |
| NAT statique & Port Forwarding | NAT statique / Port Forwarding |
| Agrégation de liens (EtherChannel / LACP) | Agrégation & Redondance |
| Redondance de passerelle (HSRP) | Agrégation & Redondance |
| DHCP Relay | BigMac, NAT, Agrégation & Redondance |
| Téléphonie IP (VoIP, Cisco CME) | BigMac |
| Sécurisation des accès (SSH) | BigMac |

## 📂 Projets

### [01 · BigMac — Architecture réseau d'entreprise multi-sites](./01-bigmac)
Projet le plus complet : segmentation VLAN sur 2 sites + datacenter, routage inter-VLAN (SVI et Router-on-a-Stick), téléphonie IP, DHCP relay, sécurisation SSH.

### [02 · NAT surchargé (PAT)](./02-nat_pat)
Architecture multi-sites avec sortie Internet mutualisée via NAT dynamique overload, ACL de contrôle, routage statique et relais DHCP.

### [02b · NAT statique & Port Forwarding](./02b-nat-statique-portforwarding)
Complément au projet NAT : publication d'un serveur web interne sur Internet via NAT statique et redirection de port, combiné à du NAT overload et du routage RIP.

### [03 · VLAN Segmentation](./03-vlan-segmentation)
TP fondamental de calcul d'adressage (VLSM) et de configuration VLAN/trunking sur une topologie à trois commutateurs en chaîne.

### [04 · OSPF multi-zones](./04-ospf)
Déploiement du routage dynamique OSPF sur 4 aires distinctes (backbone + 3 zones), avec routage inter-VLAN sur commutateurs de niveau 3.

### [05 · Agrégation de liens & Redondance de passerelle](./05-aggregation-redondance)
EtherChannel (LACP) sur plusieurs liaisons inter-commutateurs, combiné à une redondance de passerelle HSRP active/passive avec bascule automatique.

---
*Portfolio en cours de continuation.*
