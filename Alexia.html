<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Alexia AI - Simulation de Workflow n8n</title>
    <style>
        /* Styles CSS pour une meilleure lisibilité */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f0f4f8; padding: 20px; }
        .container { max-width: 900px; margin: auto; background: #ffffff; padding: 30px; border-radius: 12px; box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1); }
        h1 { color: #007bff; text-align: center; border-bottom: 3px solid #007bff; padding-bottom: 10px; margin-bottom: 25px; }
        button { background-color: #28a745; color: white; padding: 12px 25px; border: none; border-radius: 6px; cursor: pointer; font-size: 16px; margin-top: 20px; transition: background-color 0.3s; display: block; width: 100%; }
        button:hover { background-color: #218838; }
        #results { margin-top: 30px; }
        .offer-card { border: 1px solid #ddd; padding: 20px; margin-bottom: 20px; border-radius: 8px; background-color: #fcfcfc; }
        .offer-card strong { color: #333; }
        .category { background-color: #007bff; color: white; padding: 4px 8px; border-radius: 4px; display: inline-block; margin-bottom: 10px; font-weight: bold; }
        pre { white-space: pre-wrap; background: #e9ecef; padding: 15px; border-radius: 6px; border-left: 5px solid #007bff; font-size: 0.9em; }
    </style>
</head>
<body>

<div class="container">
    <h1>🤖 Alexia AI - Workflow n8n Simulé (JavaScript)</h1>
    <p>Cliquez pour exécuter la chaîne de traitement complète : Scraping simulé, Analyse de la description, Génération du workflow JSON, Création du message "Alexia", et Check Doublons (utilisant le stockage local).</p>

    <button onclick="runAlexiaWorkflow()">🚀 Déclencher le Workflow Alexia</button>

    <div id="results"></div>
</div>

<script>
    // --- DONNÉES SIMULÉES (Flux RSS Upwork n8n) ---
    const SIMULATED_OFFERS = [
        {
            title: "Créer un workflow n8n pour Google Sheets et Trello",
            link: "https://www.upwork.com/jobs/1",
            description: "J'ai besoin d'automatiser l'enregistrement de leads dans Google Sheets puis de créer une carte Trello. Utilisation d'API REST pour la gestion des données.",
            budget: 1200
        },
        {
            title: "Intégration API Stripe et n8n pour facturation",
            link: "https://www.upwork.com/jobs/2",
            description: "Mettre en place un webhook pour capturer les paiements Stripe et lancer une séquence d'emails personnalisés via SendGrid.",
            budget: 350
        },
        {
            title: "Tâche de transfert de données simple avec n8n",
            link: "https://www.upwork.com/jobs/3",
            description: "J'ai un petit travail de synchronisation entre deux plateformes SaaS via n8n. Rien de complexe.",
            budget: 80
        }
    ];

    // --- LOGIQUE DE GESTION DES DOUBLONS (Stockage Local) ---
    const HISTORY_KEY = 'alexia_offers_history';
    function loadHistory() {
        try {
            return JSON.parse(localStorage.getItem(HISTORY_KEY) || '[]');
        } catch (e) {
            return [];
        }
    }
    function saveHistory(history) {
        localStorage.setItem(HISTORY_KEY, JSON.stringify(history));
    }

    // --- FONCTION PRINCIPALE : REPRODUCTION DES NŒUDS N8N ---
    function runAlexiaWorkflow() {
        const history = loadHistory();
        const resultsDiv = document.getElementById('results');
        resultsDiv.innerHTML = '';
        let processedCount = 0;
        
        // La simulation du Planification Cron/Scraper/Parser est ici.

        SIMULATED_OFFERS.forEach(offer => {
            
            // Nœud "Check Doublons"
            if (history.some(h => h.link === offer.link)) {
                return; // Ignorer l'offre si elle est déjà dans l'historique
            }

            // Nœud "Analyser description & problème"
            const descLower = offer.description.toLowerCase();
            let category = 'Workflow Simple';
            if (descLower.includes('google sheets')) {
                category = 'Google Sheets Automation';
            } else if (descLower.includes('api')) {
                category = 'API Integration';
            } else if (descLower.includes('webhook')) {
                category = 'Webhook Trigger';
            }
            offer.category = category;

            // Nœud "Générer workflow n8n"
            const templates = {
                'Google Sheets Automation': { nodes: [{ nodeType: 'GoogleSheets', operation: 'read' }], connections: {} },
                'API Integration': { nodes: [{ nodeType: 'HTTP Request', operation: 'GET' }], connections: {} },
                'Webhook Trigger': { nodes: [{ nodeType: 'Webhook', operation: 'listen' }], connections: {} },
                'Workflow Simple': { nodes: [{ nodeType: 'Set', operation: 'set' }], connections: {} }
            };
            offer.workflowJson = templates[category];

            // Nœud "Créer guide détaillé"
            let guide = '1️⃣ Importer workflow\n2️⃣ Configurer nodes\n3️⃣ Tester';
            if (category === 'Google Sheets Automation') {
                guide = '1️⃣ Importer workflow\n2️⃣ Configurer Google Sheets\n3️⃣ Lier node read\n4️⃣ Tester';
            } else if (category === 'API Integration') {
                guide = '1️⃣ Importer workflow\n2️⃣ Configurer HTTP Request\n3️⃣ Tester';
            }
            offer.guideInstallation = guide;

            // Nœud "Créer message Alexia"
            let note = 'Livraison sous 24h.';
            if (offer.budget >= 1000) {
                note = 'Priorité haute pour livraison ultra-rapide.';
            }
            
            const message = `
Bonjour [Nom client],
Je suis Alexia, votre assistante virtuelle.
J'ai préparé une solution n8n pour votre demande: ${offer.title} (Budget: ${offer.budget}€)
Workflow prêt à importer (Catégorie: ${category})

**Guide détaillé**
${offer.guideInstallation}

${note}
Portfolio: <LIEN_PORTFOLIO>
(Fichier workflow sécurisé par: Loveless@1991)
            `.trim();
            offer.message = message;

            // Affichage des résultats (Simulation d'Envoi Email/WhatsApp)
            const card = document.createElement('div');
            card.className = 'offer-card';
            card.innerHTML = `
                <div class="category">${offer.category}</div>
                <h3>${offer.title}</h3>
                <p><strong>Lien:</strong> <a href="${offer.link}" target="_blank">${offer.link}</a></p>
                <p><strong>Budget:</strong> ${offer.budget}€</p>
                <p><strong>Workflow JSON généré:</strong></p>
                <pre>${JSON.stringify(offer.workflowJson, null, 2)}</pre>
                <p><strong>Message Alexia prêt à envoyer:</strong></p>
                <pre>${offer.message}</pre>
            `;
            resultsDiv.appendChild(card);
            
            // Nœud "Logging complet"
            history.push({ link: offer.link, title: offer.title, date: new Date().toISOString() });
            processedCount++;
        });

        // Mise à jour de l'historique
        saveHistory(history);
        
        if (processedCount > 0) {
            resultsDiv.insertAdjacentHTML('afterbegin', `<p style="color: green; font-weight: bold;">✅ Succès ! ${processedCount} nouvelle(s) offre(s) traitée(s) et loggée(s).</p>`);
        } else {
            resultsDiv.insertAdjacentHTML('afterbegin', `<p style="color: orange; font-weight: bold;">⚠️ Aucune nouvelle offre à traiter. (Toutes les offres simulées étaient des doublons.)</p>`);
        }
    }
</script>

</body>
</html>
