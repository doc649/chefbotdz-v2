# 🤖 ChefBot DZ

ChefBot DZ est un bot Telegram intelligent qui aide les utilisateurs à générer des idées de repas, planifier leurs menus, estimer les calories, et créer des listes de courses en fonction des ingrédients disponibles.

---

## 🔧 Fonctionnalités

- 📸 Lecture d'ingrédients via image (GPT-4 Vision)
- 🍲 Génération automatique de recettes traditionnelles
- 🧮 Estimation des valeurs caloriques
- 🛍️ Génération de listes de courses personnalisées
- 🗓️ Planification de menus sur plusieurs jours
- 🔁 Prise en charge des messages texte + image

---

## 🛠️ Technologies utilisées

- Python 3
- Flask + Gunicorn (serveur)
- Render (hébergement)
- OpenAI GPT-4 (Vision & Turbo)
- Telegram Bot API
- SQLite

---

## 📦 Installation rapide (local)

```bash
git clone git@github.com:doc649/chefbotdz-v2.git
cd chefbotdz-v2
pip install -r requirements.txt
python main.py
