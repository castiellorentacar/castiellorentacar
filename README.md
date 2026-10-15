<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Castiello Rent a car | Noleggio Auto a Lungo Termine</title>
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --accent-hover: #1d4ed8;
            --light: #f8fafc;
            --text: #334155;
            --success: #10b981;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Roboto, sans-serif; }
        body { background-color: var(--light); color: var(--text); line-height: 1.6; }
        header { background: white; padding: 1.2rem 5%; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 2px 10px rgba(0,0,0,0.05); position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 1.6rem; font-weight: 800; color: var(--primary); letter-spacing: -0.5px; }
        .logo span { color: var(--accent); }
        .hero { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); color: white; padding: 6rem 5%; text-align: center; }
        .hero h1 { font-size: 3rem; font-weight: 800; margin-bottom: 1.5rem; line-height: 1.2; }
        .hero p { font-size: 1.25rem; max-width: 700px; margin: 0 auto 2.5rem; color: #94a3b8; }
        .btn { display: inline-block; background: var(--accent); color: white; padding: 0.9rem 2.2rem; text-decoration: none; border-radius: 6px; font-weight: 600; transition: 0.2s; border: none; cursor: pointer; font-size: 1rem; }
        .btn:hover { background: var(--accent-hover); transform: translateY(-1px); }
        .container { max-width: 1140px; margin: 5rem auto; padding: 0 1.5rem; }
        .section-title { text-align: center; margin-bottom: 3.5rem; font-size: 2.2rem; font-weight: 700; color: var(--primary); }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2.5rem; }
        .card { background: white; padding: 2.5rem; border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.03); border: 1px solid #e2e8f0; transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,0.08); }
        .card h3 { margin-bottom: 1rem; color: var(--primary); font-size: 1.4rem; }
        .benefits-box { background: white; padding: 4rem 2rem; border-radius: 16px; box-shadow: 0 4px 25px rgba(0,0,0,0.02); border: 1px solid #e2e8f0; max-width: 800px; margin: 0 auto; }
        .checklist { list-style: none; }
        .checklist li { font-size: 1.15rem; margin-bottom: 1.2rem; display: flex; align-items: center; color: var(--primary); font-weight: 500; }
        .checklist li::before { content: "✓"; color: var(--success); font-weight: 900; margin-right: 15px; font-size: 1.4rem; }
        .form-section { background: white; padding: 3.5rem 2.5rem; border-radius: 16px; box-shadow: 0 20px 40px rgba(0,0,0,0.06); border: 1px solid #e2e8f0; max-width: 650px; margin: 0 auto; }
        .form-group { margin-bottom: 1.5rem; text-align: left; }
        .form-group label { display: block; margin-bottom: 0.6rem; font-weight: 600; color: var(--primary); font-size: 0.95rem; }
        .form-group input, .form-group select { width: 100%; padding: 0.85rem; border: 1px solid #cbd5e1; border-radius: 6px; font-size: 1rem; color: var(--primary); }
        footer { background: var(--primary); color: #94a3b8; text-align: center; padding: 3rem 1.5rem; margin-top: 6rem; font-size: 0.95rem; border-top: 4px solid var(--accent); }
    </style>
</head>
<body>

    <header>
        <div class="logo">Castiello<span> Rent a car</span></div>
        <a href="#preventivo" class="btn" style="padding: 0.6rem 1.4rem; font-size: 0.9rem;">Contattaci</a>
    </header>

    <section class="hero">
        <h1>Noleggio Auto a Lungo Termine <br>Su Misura con Castiello Rent a car.</h1>
        <p>Scegli la tua prossima auto senza pensieri. Un unico canone mensile fisso tutto incluso. Soluzioni flessibili per privati e aziende.</p>
        <a href="#preventivo" class="btn">Richiedi un Preventivo Gratuito</a>
    </section>

    <section class="container">
        <h2 class="section-title">Perché Scegliere Castiello Rent a car</h2>
        <div class="grid">
            <div class="card">
                <h3>Nessun Capitale Immobilizzato</h3>
                <p>Non devi pagare l'intero valore dell'auto. Scegli l'anticipo che preferisci (anche Zero) e paghi solo il reale utilizzo.</p>
            </div>
            <div class="card">
                <h3>Zero Ansia da Svalutazione</h3>
                <p>Al termine del contratto ti basta restituire le chiavi dell'auto. Della svalutazione dell'usato ce ne occupiamo noi.</p>
            </div>
            <div class="card">
                <h3>Flessibilità Totale</h3>
                <p>Personalizzi la durata del noleggio e la soglia dei chilometri annui in base alle tue reali necessità.</p>
            </div>
        </div>
    </section>

    <section class="container">
        <h2 class="section-title">Cosa Include il Nostro Canone</h2>
        <div class="benefits-box">
            <ul class="checklist">
                <li>Copertura Assicurativa Totale (RCA, Kasko, Furto e Incendio)</li>
                <li>Manutenzione Ordinaria e Straordinaria inclusa</li>
                <li>Assistenza Stradale e Soccorso H24 in tutta Europa</li>
                <li>Tassa di possesso (Bollo Auto) interamente azzerata</li>
                <li>Gestione di tutte le pratiche burocratiche</li>
            </ul>
        </div>
    </section>

    <section id="preventivo" class="container">
        <h2 class="section-title">Richiedi un Preventivo Personale</h2>
        <div class="form-section">
            <form action="https://formspree.io" method="POST">
                <div class="form-group">
                    <label for="name">Nome Completo / Ragione Sociale</label>
                    <input type="text" id="name" name="name" required placeholder="Es. Mario Rossi">
                </div>
                <div class="form-group">
                    <label for="email">Indirizzo Email</label>
                    <input type="email" id="email" name="email" required placeholder="nome@esempio.it">
                </div>
                <div class="form-group">
                    <label for="phone">Telefono / WhatsApp</label>
                    <input type="tel" id="phone" name="phone" required placeholder="Es. 333 1234567">
                </div>
                <div class="form-group">
                    <label for="car">Tipologia di Veicolo</label>
                    <select id="car" name="car">
                        <option value="citycar">City Car / Utilitaria</option>
                        <option value="suv">SUV / Crossover</option>
                        <option value="berlina">Berlina / Station Wagon</option>
                        <option value="commerciale">Veicolo Commerciale</option>
                    </select>
                </div>
                <button type="submit" class="btn" style="width: 100%; padding: 1rem;">Invia la Richiesta a Castiello Rent a car</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Castiello Rent a car. Tutti i diritti riservati.</p>
    </footer>

</body>
</html>

