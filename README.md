# 🚗 Robot Suiveur de Ligne  


## Description  
Ce projet est un **robot autonome suiveur de ligne** basé sur **Arduino**. Il utilise des **capteurs infrarouges** pour détecter et suivre une ligne tracée au sol. Le robot ajuste automatiquement sa trajectoire pour rester sur la ligne en contrôlant ses moteurs via un **driver moteur**.  

## Matériel Utilisé  
- **Arduino Uno**  
- **Capteurs infrarouges (IR) TCRT5000 ou similaires**  
- **Module Driver L298N** (ou L293D)  
- **Moteurs à courant continu avec roues**  
- **Batterie Li-Ion / Pack d’alimentation**  
- **Châssis de robot**  

## Fonctionnement  
1. Les **capteurs IR** détectent la présence ou l'absence de la ligne noire.  
2. L'**Arduino** interprète les signaux des capteurs et ajuste la direction du robot.  
3. Le **driver moteur** contrôle les moteurs pour corriger la trajectoire.  
4. Si le robot détecte que la ligne est perdue, il effectue des ajustements pour la retrouver.  

## Schéma de câblage:  
![image](https://github.com/user-attachments/assets/91ca073e-79dc-475f-9667-e97f029ab780)

## Photos du Projet:
<img width="286" alt="image" src="https://github.com/user-attachments/assets/8e947b44-97e7-4c95-9b61-104502af32f0" />
![image](https://github.com/user-attachments/assets/a6d2b34c-51ad-4061-b186-7b1003660a3d)
![image](https://github.com/user-attachments/assets/9026c11c-7bc7-49e0-b002-e7b4055c640d)





