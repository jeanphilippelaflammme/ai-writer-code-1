# appdev
App Development CrossPlatform
import json

# Créer un dictionnaire Python
person = {
    'nom': 'JP LAFLAMME ',
    'age': 30,
    'ville': 'New York'
}

# Convertir le dictionnaire en JSON
person_json = json.dumps(person)

# Afficher le JSON
print(person_json)
