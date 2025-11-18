# DynamicTeaching

## ✨ Was ist der Dynamic Explainer?

Schluss mit der Einheitserklärung\! **Der Dynamic Explainer ist die Antwort\!**

Dieses elegante Python-Projekt, aufgebaut mit der Power von Streamlit, generiert **dynamisch** und **kontextsensitiv** Erklärungen zu komplexen Themen aus verschiedenen Fächern und bietet diese in **unterschiedlichen Schwierigkeitsgraden** an. Es ist der ultimative Beweis, wie moderne Python-Tools genutzt werden können, um den Lernprozess zu individualisieren.

**Das Ziel:** Erklärungen auf Knopfdruck, die **perfekt zum aktuellen Wissensstand** des Lernenden passen\! Biete Schülern eine **adaptive Quelle** für inhaltliches Verständnis.

-----

## 🎯 Kern-Features (Die Highlights)

  * **⚡️ Kontextuelles Erklären:** Basierend auf dem gewählten **Thema** (z.B. Photosynthese, Quantenmechanik, Konjunktiv II) generiert die App eine maßgeschneiderte Erklärung.
  * **🛠️ Dynamische Schwierigkeit:** Wähle den gewünschten **Level** (z.B. **Level 1: Einfach & Analog** bis **Level 10: Akademisch & Mathematisch**) mithilfe eines intuitiven Sliders.
  * **🧠 Adaptive Tiefe:** Die App steuert die **Komplexität des Vokabulars**, die **Länge der Sätze** und die **Anzahl der Fachbegriffe** basierend auf dem gewählten Level.
  * **🧑‍💻 Clean Architecture:** Klar definierte Funktionen zur Generierung (`GenerateExplanation`), Themenauswahl und Level-Steuerung machen den Code **lesbar, wartbar** und **erweiterbar**.

-----

## 🚀 Installation & Launch

Sie benötigen Python 3.x und Streamlit (sowie eine Implementierung zur Erklärungserzeugung, z.B. über eine API oder ein lokales Modell).

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    cd YOUR_REPO_NAME
    ```

2.  **Install Dependencies:**

    ```bash
    pip install streamlit 
    # Optional: pip install requests (für API-Calls zur Generierung)
    ```

3.  **Set Up Data Structure (Themenliste):**
    Stellen Sie sicher, dass Sie eine `topics.json` oder eine ähnliche Datei haben, die die **verfügbaren Themen** pro Fach enthält.

4.  **Run the App:**

    ```bash
    streamlit run YOUR_MAIN_FILENAME.py
    ```

    *(Ersetzen Sie `YOUR_MAIN_FILENAME.py` durch den tatsächlichen Namen Ihrer Python-Datei, z.B. `app.py` oder `explainer.py`)*

-----

## 💡 Wie es funktioniert (Anwendung)

Sobald die Streamlit-App im Browser geöffnet ist:

1.  Gib deinen Namen ein (für eine freundliche Ansprache\!).
2.  Wähle das **Fach** und das **spezifische Thema** aus dem Dropdown-Menü.
3.  Definiere den gewünschten **Erklär-Level** (1-10) mithilfe des Sliders.

**Resultat:** Die App zeigt sofort eine **frisch generierte Erklärung** an, die **stilistisch und inhaltlich exakt** auf das gewählte Level zugeschnitten ist\!

-----

## 🛠️ Technology Stack

  * **Python:** Die Basis für die gesamte Logik und die Steuerung der Komplexität.
  * **Streamlit:** Ermöglicht den Bau einer **ansprechenden, interaktiven** Webanwendung mit minimalem Aufwand.
  * **Generative Logik:** Die Kernkomponente, die die Erklärungsinhalte basierend auf den Level-Parametern generiert (z.B. mittels definierter Funktionen oder einer externen KI-Engine).

-----

## 🤝 Contributing

Dieses Projekt zeigt, wie leistungsfähig eine kleine Python-Anwendung für die Bildung sein kann. Haben Sie Ideen, wie der Explainer noch besser werden kann (z.B. visuelle Diagramme je Level, Vokabel-Glossar-Funktion)?

1.  Fork the Repository.
2.  Create your Feature Branch (`git checkout -b feature/AmazingExplanation`).
3.  Commit your changes (`git commit -m 'Add some AmazingExplanation logic'`).
4.  Push to the Branch (`git push origin feature/AmazingExplanation`).
5.  Open a Pull Request.

-----

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

-----

> **Built with 🖤 and Python 🐍 by [GilbertZennerDev]**