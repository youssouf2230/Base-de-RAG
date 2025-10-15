# Qu’est-ce que RAG (Retrieval-Augmented Generation) ?

##Résumé :

RAG est une approche qui combine deux éléments :

un moteur de recherche sémantique (retrieval),

un modèle de langage (LLM, comme Mistral ou GPT).

L’objectif est de générer des réponses plus précises en s'appuyant non seulement sur ce que le modèle sait déjà, mais aussi sur des documents externes.

Fonctionnement de RAG :

Des documents (PDF, textes, pages web, etc.) sont convertis en vecteurs via un modèle d’embedding.

Ces vecteurs sont stockés dans un index vectoriel.

Lorsqu'une question est posée :

l’index est consulté pour retrouver les documents les plus pertinents ;

le modèle de langage génère une réponse à partir de ces documents.

Pourquoi utiliser RAG :

On peut interroger ses propres documents, pas juste la base de connaissances du LLM.

Le système peut être mis à jour facilement (ajout de nouveaux documents).

C’est adapté pour des cas comme :

FAQ personnalisée,

chatbot sur des documents internes,

moteur de réponse pour des bases juridiques, médicales, etc.
