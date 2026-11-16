# HandCoach Mobile

Version mobile de HandCoach, orientée **consultation sur le terrain**.

Même compte et mêmes données que la version web (Supabase).  
Interface adaptée au tactile, en **lecture seule** pour éviter les modifications accidentelles pendant l’entraînement.

---

## Présentation

Sur téléphone ou tablette, HandCoach Mobile permet de :

- Se connecter avec le même compte que la version web
- Consulter la bibliothèque d’exercices et de séances
- Afficher le schéma sur le terrain (y compris le second terrain « Évolution »)
- Lire les consignes, variantes et objectifs
- Rejoindre une bibliothèque partagée (code d’invitation, lecture)
- Imprimer un exercice ou une séance
- Rester synchronisé avec le cloud

La **création et la modification** des exercices se font sur la version web (ordinateur).

---

## Pourquoi une version lecture seule ?

Sur le terrain, l’usage principal est de **suivre la séance**, pas de redessiner un exercice au doigt.

Avantages :

- Moins d’erreurs de manipulation
- Interface plus simple et lisible
- Données protégées contre les modifications involontaires
- Édition complète conservée sur ordinateur

Les fonctions d’édition sont **masquées** (pas supprimées) : elles peuvent être réactivées rapidement si besoin (marqueur `MOBILE-READONLY` dans le code).

---

## Stack technique

- HTML / CSS / JavaScript (vanilla)
- Même backend que la version web : **Supabase** (Auth + PostgreSQL)
- Interface responsive / tactile
- Hébergement : Netlify (ou équivalent)

---

## Fonctionnalités

| Fonction | Mobile |
|----------|--------|
| Connexion / déconnexion | Oui |
| Consultation exercices & séances | Oui |
| Affichage terrain + second terrain | Oui |
| Impression | Oui |
| Rejoindre une bibliothèque (lecture) | Oui |
| Créer / modifier un exercice | Non (masqué) |
| Créer une bibliothèque | Non (masqué) |
| Palette pions / crayon | Non (masquée) |
| Déconnexion après inactivité | Oui (même logique que le web) |

---

## Utilisation

1. Ouvrir le lien mobile dans le navigateur du téléphone
2. Se connecter avec le compte HandCoach
3. Ouvrir la bibliothèque (menu ☰)
4. Consulter un exercice ou une séance
5. Imprimer si besoin

Astuce : sur mobile, « Partager → Sur l’écran d’accueil » pour une icône type application.

---

## Lien avec la version web

- **Même compte** Supabase  
- **Mêmes exercices et séances**  
- Web = création / édition  
- Mobile = consultation sur le terrain  

---

## Contexte

Dérivée de HandCoach web, adaptée pour un usage réel pendant les entraînements.

Même démarche : outil concret, construit progressivement avec l’aide d’une IA, à partir d’un besoin d’entraîneur.

---

## Auteur

Projet personnel — coach de handball.  
Besoin terrain → outil numérique (web + mobile).

<img width="1220" height="2289" alt="Screenshot_2026-11-16-21-20-57-477_com android chrome-edit" src="https://github.com/user-attachments/assets/51d0457c-a0e2-44f4-a0cb-5a13c0672591" />
<img width="1220" height="2293" alt="Screenshot_2026-11-16-21-19-33-116_com android chrome-edit" src="https://github.com/user-attachments/assets/5a52f914-c305-4618-9d56-6ec2c78167ae" />
<img width="1220" height="2260" alt="Screenshot_2026-11-16-21-19-19-965_com android chrome-edit" src="https://github.com/user-attachments/assets/1ee98238-5a33-48e3-b7d8-de98548c8a7a" />
<img width="1220" height="2286" alt="Screenshot_2026-11-16-21-18-47-241_com android chrome-edit" src="https://github.com/user-attachments/assets/d390553f-9a46-4fa6-83cf-9a1f558a1863" />

