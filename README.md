# ESP32 FreeRTOS - LED Blink & Message série

## Objectif
Ce projet met en place un système multi-tâches sur ESP32 en utilisant FreeRTOS.
Deux tâches tournent en parallèle et indépendamment :
- une tâche qui fait clignoter une LED
- une tâche qui affiche un message dans le moniteur série toutes les 3 secondes

## Technologies
- ESP32
- FreeRTOS (xTaskCreate, vTaskDelay)
- C/C++ (Arduino framework)
- Simulation réalisée sur Wokwi

## Auteure
Amal Nasser
