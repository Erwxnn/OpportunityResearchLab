# Point de reprise

- Dernière mise à jour : 2026-10-15
- Dernier lot : Lot 2 (2026-10-15) : validation commerciale d'OPP-0001 par market-validator (un seul sous-agent). Recommandation : ABANDON. OPP-0001 passe en rejete_provisoire (46/100, preuve C).
- Lot précédent : Lot 1 (initialisation + repérage limité par l'agent principal).
- Pistes découvertes : 3 (OPP-0001 à OPP-0003)
- Pistes qualifiées : 0
- Secteurs explorés : conformité fiscale B2B Côte d'Ivoire (FNE) ; automatisation WhatsApp pour boutiques ; plugins d'encaissement Mobile Money WooCommerce ; contrainte transverse : encaissement international depuis la CI.
- Recherches déjà effectuées à ne pas répéter :
  - « plugin WooCommerce Wave Orange Money MTN Côte d'Ivoire prix licence »
  - « chatbot WhatsApp commandes boutique Abidjan tarif mensuel FCFA »
  - « facture normalisée électronique FNE Côte d'Ivoire DGI obligation 2025 logiciel API »
  - « module Odoo FNE Côte d'Ivoire prix » (module l10n_ci_fne_einvoice v19 retiré de l'Odoo App Store)
  - « logiciel facturation FNE agréé DGI abonnement FCFA PME »
  - « DGI FNE liste éditeurs intégrateurs agréés interconnexion API » (aucune liste officielle trouvée par moteur de recherche)
  - Lot 2 (market-validator, 13 requêtes) : documentation API fne.dgi.gouv.ci / clé API ; tarifs logiciels FNE « FCFA/mois » (fr, en, mode extended) ; communiqué DGI interfaçage API ; intégrateurs FNE WooCommerce/Odoo/Dolibarr ; sandbox/clé API développeur ; tarifs neocode.ci ; Kompto agrément 24 900 ; Octogone FNE IVOIRE 50 000 FCFA/an ; plaintes commerçants/double saisie/suspension des contrôles ; éditeurs agréés / ONECCA.
  - Pages inaccessibles au lot 2 : fne.dgi.gouv.ci (certificat), digitalmag.ci (403), fne.myoctogone.com (DNS), kompto.com/agrement-dgi et /tarifs (404).
  - « PayPal Côte d'Ivoire recevoir paiements / Payoneer freelances ivoiriens »
- Pistes rejetées et raisons :
  - OPP-0001 (rejet provisoire, lot 2) : critère d'arrêt (a) non satisfait. L'accès API demande une revue de conformité DGI et l'autorisation du DG. Un agrément d'éditeur est probable (coût, délai et conditions inconnus). Le modèle multi-clients/BYOK n'est pas confirmé. Les spécifications changent (communiqué DGI du 14/09/2026 : mise en conformité avant le 29/10/2026, sinon suspension des clés possible). Aucune volonté de payer prouvée. Le connecteur à 5 000 FCFA/mois coûterait autant que des SaaS complets qui incluent la FNE (Madata 15 000/mois vérifié ; Octogone ~4 167/mois et Kompto 24 900/mois non vérifiés). Réouverture seulement si l'opérateur obtient de la DGI une réponse écrite favorable (action externe : à décider par l'opérateur).
  - OPP-0003 (rejet provisoire) : plugins gratuits sur WordPress.org et agrégateurs établis (CinetPay, PayDunya, Hub2) ; aucun segment mal servi repéré. Examen superficiel.
  - OPP-0002 (en attente, non rejetée) : alternatives gratuites (WhatsApp Business), sources presque uniquement de prestataires, aucune dépense locale vérifiée.
- Sources ou hypothèses à revérifier :
  - Tarif du cachet FNE (20 XOF TTC/FNE, 15 XOF/RNE) : recoupé au lot 2 (AfroTools + Abidjan.net, séance CGECI/DGI 14/08/2025), toujours pas vu sur le portail DGI.
  - Prix Octogone (50 000 FCFA/an) et Kompto (24 900 FCFA/mois) : vus seulement dans des extraits de recherche.
  - Procédure d'interconnexion API DGI (mai 2025) : un éditeur tiers peut-il servir plusieurs contribuables, ou chaque entreprise doit-elle obtenir sa propre autorisation ?
  - Tous les prix Kolonell (prestataire, contenu commercial) : non fiables tant qu'ils ne sont pas recoupés.
  - Réception de paiements internationaux depuis la CI : PayPal en réception non confirmé ; Payoneer documenté seulement par des blogs commerciaux ; rachat de Payoneer par Nuvei annoncé le 15/06/2026 (conditions susceptibles de changer). Contrainte à vérifier avant toute piste vendue à l'international.
- 2026-10-15 : portée mondiale confirmée par l'opérateur (aucune zone prioritaire). L'opérateur a des cartes Visa internationales : payer les coûts à l'étranger n'est pas un blocage ; recevoir les paiements reste à vérifier piste par piste.
- Prochaine tâche prioritaire : aucune piste ouverte. Lot 3 proposé : repérage d'un nouveau secteur dans n'importe quel pays (opportunity-scout ou agent principal), hors conformité fiscale CI, paiements Mobile Money et bots WhatsApp déjà couverts. Pour les pistes vendues hors CI, vérifier en premier les moyens d'encaissement ouverts aux résidents ivoiriens (places de marché et processeurs). Privilégier des pistes où une dépense existante est observable (preuve A/B) et vendables sans agrément réglementaire.
- Option parallèle sans quota (opérateur uniquement) : écrire à la DGI (e-impots@dgi.gouv.ci ou support FNE) pour demander si un éditeur peut raccorder plusieurs contribuables avec une clé par contribuable, sans agrément payant. Si la réponse écrite est favorable, rouvrir OPP-0001 avec le test prévu (voir CSV, prochaine_action).
- Critère d'arrêt du lot 3 : au plus 2 pistes examinées ; arrêter dès qu'une piste atteint un niveau de preuve B ou que les recherches ne trouvent que des prix de prestataires.
- Dernier identifiant attribué : OPP-0003

## État de la recherche
Lot 2 terminé. Aucune piste qualifiée, aucune piste ouverte. OPP-0001 est rejetée provisoirement (52 → 46/100, preuve C). Note : market-validator a dépassé son budget (environ 14 recherches au lieu d'environ 8) ; le préciser plus fermement la prochaine fois.

## Hypothèses bloquant la qualification d'OPP-0001 (relevées le 2026-10-15 ; résultat du lot 2 : 1 non résolu/négatif, 2 aucune preuve, 3 deux prix dont un seul vérifié, 4 et 5 non prouvés, 6 cible à peine atteinte avant coûts)
1. Volonté de payer des PME hors ERP pour éviter la double saisie : aucune dépense observée (demande 12/25).
2. Accès API DGI : un éditeur tiers peut-il servir plusieurs contribuables avec une seule intégration, ou faut-il une autorisation du DG par entreprise ? Agrément éditeur requis (coût, délai) ?
3. Prix concurrents : aucun prix public vérifié (seuls chiffres : Kolonell, prestataire).
4. Segment mal servi : la plateforme/appli officielle (cachet 20 XOF/FNE, à confirmer) suffit-elle aux petites structures ?
5. Acquisition : canal cabinets comptables / CGA / groupes d'entrepreneurs non vérifié.
6. Économie : 10 000 FCFA nets/semaine ≈ 43 000 FCFA/mois ≈ 9 clients à 5 000 FCFA/mois (prix et volume non vérifiés).
Brief exécuté au lot 2 (market-validator) → recommandation ABANDON.

## Configuration
- Sous-agents créés dans `.claude/agents/` : opportunity-scout (haiku), market-validator (sonnet), opportunity-auditor (sonnet). Outils : WebSearch, WebFetch uniquement. Aucun ne peut écrire de fichier, lancer d'agent ni programmer de tâche.
- Conflit résolu le 2026-10-15 : CLAUDE.md contient désormais une « Politique d'utilisation des sous-agents » (invocation sélective à la demande, un seul par lot de préférence, l'agent principal fait lui-même ce qu'il peut faire correctement).
- 2026-10-15 : règle « Données de marché au-delà des avis en ligne » ajoutée à CLAUDE.md et aux trois sous-agents (sources de dimensionnement et de rentabilité, critères B/C des études). Budget market-validator : celui du brief, sinon une dizaine de recherches.
- Les sous-agents créés en cours de session ne sont chargés qu'à la session suivante. Depuis le lot 2, market-validator fonctionne (invocation réussie le 2026-10-15).

## Règle de priorité
Ne pas lancer de recherche si un projet de développement prioritaire nécessite le quota Claude Pro.
