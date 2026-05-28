# ETM PowerSync — Plugins

> Plugins d'équipements pour ETM PowerSync (bornes de recharge, compteurs, onduleurs) —
> portage et intégration sur [nymea.io](https://nymea.io).

Ce dépôt regroupe les plugins permettant à ETM PowerSync de communiquer avec le matériel :
bornes de recharge (EVSE), compteurs d'énergie, onduleurs et autres équipements, via Modbus
(TCP/RTU), MQTT et protocoles propriétaires.

## Contribuer

Le portage de nouveaux équipements est en cours. Les contributions sont bienvenues :

- **Nouveaux plugins** : un équipement non supporté ? Ouvrez une issue avec la référence
  et, si possible, sa documentation Modbus.
- **Registres Modbus** : les specs de registres vérifiées sont précieuses.
- **Retours terrain** : un comportement inattendu se signale via les issues.

La liste de compatibilité à jour (Supporté / Partiel / Roadmap) est publiée dans la
[documentation](https://docs.etm-powersync.fr/appareils/compatibilite/).

## Licence

[GNU General Public License v3.0](LICENSE) — © ETM-Schurig, et contributeurs evcc pour
le code dérivé.

## Liens

- Documentation : https://docs.etm-powersync.fr
- Cœur du HEMS : https://github.com/etmschurig/powersync-core
