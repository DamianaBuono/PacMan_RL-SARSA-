# Reinforcement Learning per Pac-Man

**Sviluppo di un agente intelligente tramite algoritmi di RL**

 ## Descrizione del progetto

Questo repository contiene il report del progetto “Sviluppo di un Agente Intelligente per il Gioco Pac-Man tramite Reinforcement Learning”, realizzato da Damiana Buono e Martina Girolamo (Giugno 2025).

L’obiettivo del lavoro è progettare, implementare e analizzare un agente autonomo in grado di giocare a **Pac-Man** attraverso tecniche di **Reinforcement Learning (RL)**.
Il progetto non si limita a far sopravvivere l’agente, ma mira a **ottimizzare il punteggio** bilanciando esplorazione, sopravvivenza e raccolta di risorse.

## Obiettivi dell’agente

L’agente deve:

*navigare il labirinto evitando i fantasmi;

*raccogliere il maggior numero possibile di bacche;

*sfruttare power-up e dinamiche di gioco;

*adattarsi a diverse configurazioni e scenari.

## Contesto teorico

Il Reinforcement Learning si basa sull’interazione agente-ambiente:
l’agente esegue azioni → osserva lo stato successivo → riceve ricompense → migliora la sua politica.

Pac-Man rappresenta un ambiente ideale per applicare il RL perché offre:

* **stati ben definiti** (posizione, oggetti, fantasmi);

* **azioni discrete** (su/giù/sinistra/destra);

* **dinamiche stocastiche** che rendono il problema non banale;

* **obiettivi multipli**  e trade-off fra rischio e ricompensa.

## Metodologia

Il progetto include:

* modellazione dell’ambiente di gioco;

* definizione formale di stati e azioni;

* progettazione di una funzione di ricompensa efficace;

* addestramento dell’agente tramite simulazioni multiple;

* confronto tra differenti algoritmi di Reinforcement Learning.

L’obiettivo finale è valutare quale tecnica permetta le migliori performance in termini di punteggio, sopravvivenza e stabilità dell’apprendimento.
