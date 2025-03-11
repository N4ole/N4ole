```python
pseudo = "Naole"
profession = "étudiant"
localisation = "France (77)"
connaissances = ["Développement web", "Gestion de projet", "pyhton"]
hobbies = ["Tech", "Jeux-vidéos", "Musique"]


def presentation():
    print(f"👋 Salut, moi c'est (pseudo).")
    print(f"💼 Profession : {profession}.")
    print(f"📍 Localisation : {localisation}.")
    print("🎯 connaissances :")
    for domaine in domaines_d_expertise:
        print(f"   - {domaine}")
    print("🌱 Centres d'intérêt :")
    for hobby in hobbies:
        print(f"   - {hobby}")


valeurs = [
    "📌 atteindre mes objectifs",
    "🤝 Partager la connaissance",
    "🚀 travailler ensemble",
    "💡 discuter en groupe"
]

def afficher_valeurs():
    print("\n🔹 Valeurs :")
    for valeur in valeurs:
        print(f"   - {valeur}")

contacts = {
    "GitHub": "https://github.com/N4ole",
    "X": "https://x.com/Naole77",
    "Site projet": "https://www.trajectair.com"
}

def afficher_contacts():
    print("\n📬 Me retrouver sur :")
    for plateforme, lien in contacts.items():
        print(f"   - {plateforme} : {lien}")

if __name__ == "__main__":
    presentation()
    afficher_valeurs()
    afficher_contacts()
```
