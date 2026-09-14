# HALVETH Choice / Plural Identity Protocol

Version 0.1 - public proposal

## Deutsch

Jeder Mensch bestimmt seine eigene Identität. Binäre, nichtbinäre, fluide, multiple, offene und selbst gewählte Beschreibungen stehen gleichberechtigt nebeneinander. Niemand muss eine vorgegebene Kategorie übernehmen oder seine Selbstdefinition rechtfertigen.

Selbstwahl ist freiwillig, veränderbar und jederzeit widerrufbar. Es gibt keine Rangordnung der Identitäten, keinen Zwang zur Übereinstimmung und keinen Anspruch, über die Identität anderer zu verfügen. Zustimmung gilt nur für den ausdrücklich gewählten Zweck und kann jederzeit beendet werden. Wer einen gemeinsamen Raum verlassen oder einen anderen Weg gehen möchte, darf dies ohne Abwertung tun; die Grenzen anderer bleiben dabei bestehen.

Digitale Systeme können Informationen technisch als `0` und `1` darstellen. Diese Codierung beschreibt die Repräsentation von Daten, nicht den Wert, die Würde, den Körper oder die Identität eines Menschen. Menschen sind niemals auf ein Bit, ein Merkmal oder eine Kategorie reduzierbar.

## English

Every person defines their own identity. Binary, non-binary, fluid, multiple, open, and self-chosen descriptions coexist as equals. No one must accept a prescribed category or justify their self-definition.

Self-identification is voluntary, revisable, and revocable at any time. No identity ranks above another, no one can be forced into agreement, and no one may claim authority over another person's identity. Consent applies only to its expressly chosen purpose and may be withdrawn at any time. Anyone may leave a shared space or follow another path without being devalued, while respecting the boundaries of others.

Digital systems may technically represent information through `0` and `1`. This encoding describes data representation; it does not define a person's worth, dignity, body, or identity. A human being can never be reduced to a bit, a trait, or a category.

## Minimal data model

```json
{
  "protocol": "HALVETH_CHOICE",
  "version": "0.1",
  "subject": "self",
  "identity": {
    "labels": ["self-defined"],
    "freeText": "",
    "pronouns": [],
    "openEnded": true
  },
  "consent": {
    "voluntary": true,
    "purpose": "",
    "visibility": "private",
    "revocable": true
  },
  "principles": [
    "equal_dignity",
    "no_hierarchy",
    "no_coercion",
    "self_definition",
    "right_to_revise",
    "right_to_leave",
    "respect_for_boundaries",
    "bits_are_representation_not_personhood"
  ]
}
```
