
🧠 TL;DR
Custom DNS blocklist for AdGuard Home focused on:
	•	🔐 Privacy – reduziert Telemetrie (Microsoft, Amazon, Apple)
	•	🚫 DNS Bypass Protection – blockiert DoH-Resolver
	•	👁 Visibility – behält wichtige Tracker sichtbar im Querylog
	•	⚖️ Stability first – keine aggressiven Breaking-Rules
👉 Ergänzt OISD / AdGuard / HaGeZi – ersetzt sie nicht.
⸻
⚙️ Usage
Add to AdGuard Home:
https://raw.githubusercontent.com/RGietz/adguard-lists/main/custom-global.txt
⸻
🧩 Philosophy
Policy-driven DNS filtering, not just blocklist stacking
	•	bewusst ausgewählte Regeln
	•	keine unnötige Redundanz
	•	klare Struktur & Wartbarkeit
⸻
⚠️ Notes
	•	$client-Regeln sind nicht enthalten (lokal verwalten)
	•	Apple Core Services bleiben explizit erlaubt
	•	einige Domains sind bewusst enthalten für Transparenz im Log
