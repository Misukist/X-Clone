# 🐦 X Clone

**Live Demo:** [https://x-clone-2pfe.onrender.com/](https://x-clone-2pfe.onrender.com/)

> ⚠️ Huomio: Jos luot uuden käyttäjän sovellukseen, **älä käytä salasanaa, jota käytät muualla**. Tämä on vain testi- ja portfolio-projekti.

![Twitter Clone Screenshot](./frontend/public/Readme/Twitter_Showcase.png)

##  📖 Projektin kuvaus
Tämä on Twitterin kaltainen klooni, jossa käyttäjät voivat luoda tilejä, kirjautua sisään ja julkaista viestejä. Projekti on rakennettu modernilla tech-stackilla React/Vite frontendillä ja Node.js/Express backendillä.  

Sovelluksessa on toteutettu mm. seuraavat ominaisuudet:

- 🔑 Käyttäjän rekisteröinti ja kirjautuminen JWT-tunnistuksella
- 👤 Profiilien näyttäminen ja muokkaaminen
- 📝 Viestien (postien) luominen ja listaaminen
- 🔔 Notifikaatiot ja interaktiot käyttäjien välillä

---

## 🛠 Teknologiat

### 💻 Frontend
- React + Vite
- Tailwind CSS
- Chakra UI
- React Router
- React Query

### ⚙️ Backend
- Node.js + Express
- MongoDB + Mongoose
- JWT Authentication
- Cookie-parser
- Cloudinary (kuvien hallinta)

---

## 🚀 Asennus ja käyttö

1. Klonkaa repositorio:

    git clone https://github.com/<username>/X-Clone.git
    cd X-Clone


2. Asenna backendin riippuvuudet:

    npm install


3. Asenna frontendin riippuvuudet:

    npm install --prefix frontend


4. Asenna backendin riippuvuudet:

    npm install


5. Luo .env tiedosto juureen ja lisää tarvittavat environment-muuttujat:

    MONGO_URI=<MongoDB connection string>
    JWT_SECRET=<JWT secret>
    CLOUDINARY_CLOUD_NAME=<Cloudinary cloud name>
    CLOUDINARY_API_KEY=<Cloudinary API key>
    CLOUDINARY_SECRET=<Cloudinary secret>


6. Käynnistä kehityspalvelin:

    npm run dev




