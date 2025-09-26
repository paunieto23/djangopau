# StreamEvents

## ✨ Objectius
Aplicació per gestionar esdeveniments i usuaris, amb estructura neta i preparada per treballar en equip.  
El projecte està pensat per utilitzar **Django** i, en un futur, suport per **MongoDB**.

## 🧱 Stack Principal
- Python 3.x  
- Django  
- SQLite (per defecte, es pot migrar a MongoDB)  
- HTML / CSS (plantilles i estils bàsics)  

## 📂 Estructura Simplificada
streamevents/
│── manage.py
│── config/
│── users/
│── templates/
│ └── base.html
│── static/
│ └── css/
│ └── main.css
│── media/ # (ignorat per Git)
│── fixtures/ # (opcional: dades d’exemple)
│── seeds/ # (opcional: scripts d’ompliment)
│── requirements.txt
│── README.md
│── .gitignore
│── env.example


## ✅ Requisits previs
- Python 3.10+ instal·lat  
- Pip i entorn virtual (`venv`)  
- Git  

## 🚀 Instal·lació ràpida
```bash
git clone https://github.com/usuari/streamevents.git
cd streamevents
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
