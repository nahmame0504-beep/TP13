# TP 13 - Exercice 1 : Sérialisation et Désérialisation avec Serializable

##  Objectifs Pédagogiques
- Comprendre le mécanisme fondamental de sérialisation et désérialisation d'objets Java via `Serializable`.
- Utiliser `ObjectOutputStream` et `ObjectInputStream` pour sauvegarder et restaurer des objets métiers dans des fichiers binaires.
- Gérer la compatibilité des versions de classe avec la constante `serialVersionUID`.
- Exclure des champs sensibles ou temporaires de la sérialisation à l'aide du mot-clé `transient`.
- Appliquer le pattern `try-with-resources` pour assurer la fermeture automatique des flux d'I/O.

---

## Structure du Projet

```text
TPSerialization/
└─ src/
   └─ com/example/tp/
      ├─ Employee.java
      ├─ SerializationUtil.java
      └─ TestSerialization.java
Fichier 2 : `README_EX2.md`

```markdown
# TP 13 - Exercice 2 : Sérialisation Avancée avec Externalizable

##  Objectifs Pédagogiques
- Découvrir l'interface `Externalizable` pour prendre un contrôle total sur le format binaire de sérialisation.
- Implémenter manuellement les méthodes `writeExternal` et `readExternal` de manière symétrique.
- Traiter la version du format binaire (`FORMAT_VERSION`) pour maintenir la compatibilité ascendante.
- Gérer les champs transients et recalculated en reconstruisant les données dérivées à la lecture.

---

##  Structure du Projet

```text
TPExternalizable/
└─ src/
   └─ com/example/tp/
      ├─ ChatMessage.java
      ├─ ChatHistory.java
      └─ TestExternalizable.java
```
<img width="1240" height="340" alt="EX2tp13" src="https://github.com/user-attachments/assets/dc3ca5c5-9f91-4109-ada9-b3519253afda" />
<img width="1251" height="320" alt="EX1tp13" src="https://github.com/user-attachments/assets/e0cc9cf2-e250-4dce-b709-61093f696e2e" />
