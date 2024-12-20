# Provisionierung verschiedener Systeme

Provisionierung von Raspberry Pis und Linux-Systemen.

## Linux Mint Provisionierung

Mit dem folgenden Befehl kann eine Linux Mint Installation provisioniert
werden. Es werden notwendige Bilbiotheken installiert und ein Image erstellt,
das über LTSP ausgerollt wird.

    curl https://raw.githubusercontent.com/tbs1-bo/provision/refs/heads/main/mint_provision.sh | bash


## Raspberry Pi - Roboterprojekt

Der folgende Befehl provisioniert einen Raspberry für das Roboter Projekt.

    curl https://raw.githubusercontent.com/tbs1-bo/provision/refs/heads/main/rpi_robo_project.sh | bash

## MQTT

Installiert einen Broker, einen grafischen Debug Client und passende Python Bibliotheken

    curl https://raw.githubusercontent.com/tbs1-bo/provision/refs/heads/main/mqtt.sh | bash


## lokale LLM mit Web-Interface

Installiert OLLAMA und OpenWbUI als Web-Interface.

    curl https://raw.githubusercontent.com/tbs1-bo/provision/refs/heads/main/local_llm.sh | bash

Zur Aktualisierung des Containers für OpenWebUI:

    curl https://raw.githubusercontent.com/tbs1-bo/provision/refs/heads/main/update_open_webui.sh | bash
