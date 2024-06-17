import json

data = {
    "name": "Ella",
    "age": 21,
    "city": "Tabriz"
}

with open('data.json', 'w') as file:
    json.dump(data, file)

with open('data.json', 'r') as file:
    loaded_data = json.load(file)

print(loaded_data)

