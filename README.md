<div align="center">

# Adrián Rodríguez Ortiz
### Backend Developer · Red Team · Security Researcher

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adrian--rodriguez--ortiz-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/adrian-rodriguez-ortiz/)
[![GitHub](https://img.shields.io/badge/GitHub-x0n3e-181717?style=flat-square&logo=github)](https://github.com/x0n3e)
[![HTB](https://img.shields.io/badge/Hack_The_Box-Active-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://app.hackthebox.com)
[![MSMK](https://img.shields.io/badge/MSMK_University-Ciberseguridad_%26_Data_Intelligence-1D3557?style=flat-square)](https://msmk.university)

</div>

---

## About

Estudiante de Ciberseguridad que se mueve igual de cómodo construyendo que rompiendo. Desarrollo backend (Python/Flask, arquitecturas propias, automatización) y seguridad ofensiva (pentests reales, análisis de malware activo reportado a INCIBE-CERT, herramientas propias de explotación y reconocimiento) van de la mano en todo lo que hago — incluido un homelab propio que uso tanto de laboratorio de red como de banco de pruebas para lo que desarrollo.

No aprendo ciberseguridad leyendo — la practico. Y lo que rompo, también sé construirlo.

```
Área principal     → Backend Development & Offensive Security
Especialización    → Python/Flask · Web Pentesting · Linux Exploitation · Malware Analysis
Certificaciones    → HTB Academy Pentester Path (en curso)
Buscando           → Prácticas / posición junior (Dev o Security) en España
```

---

## Proyectos destacados

### [Phishing_Report](https://github.com/x0n3e/Phising_Report) — Banking Trojan Dissection
> Análisis OSINT completo de campaña activa de banking trojan (familia Grandoreiro/Mekotio). Reportado a INCIBE-CERT.

Cadena de 8 stages documentada: filtro OS anti-bot → FingerprintJS Pro → HTA dropper → VBScript installer con anti-VM/AV → payload AutoIt con AES-192 + fileless execution vía `MemoryLoadLibrary`.

**Técnicas aplicadas:** Desofuscación de algoritmo custom base-573 · extracción de IOCs · análisis de PCAP · reverse de cifrado AES-192 · identificación de entry point `B080723_N()`.

`curl` `Python` `tshark` `Any.run` `VBScript` `AutoIt` `Responsible Disclosure`

---

### [SSTI-Python](https://github.com/x0n3e/SSTI-Python) — SSTI Detection Tool
> Herramienta de detección de vulnerabilidades Server-Side Template Injection con soporte multi-engine.

Payloads para Jinja2, Twig, Smarty y otros motores de templates. Desarrollada y validada en entorno CTF activo. Detección automatizada con respuesta diferencial.

`Python` `SSTI` `Web Exploitation` `CTF`

---

### [Niveles-Natas-OverTheWire-Autom-tico](https://github.com/x0n3e/Niveles-Natas-OverTheWire-Autom-tico) — Natas Auto-Solver
> Solver automático completo de todos los niveles del wargame Natas.

Automatización de: manipulación de cookies, bypass de controles de acceso, encoding/decoding, path traversal y fuzzing básico. Script único que resuelve la progresión completa de forma autónoma.

`Python` `Bash` `Web Exploitation` `Cookie Manipulation` `Path Traversal`

---

### Offensive Recon Framework *(en desarrollo, sin repo todavía)*
> Pipeline automatizado de reconocimiento para fases iniciales de pentest.

Arquitectura 3 fases: **network recon → web recon → análisis asistido por IA** (Ollama + HackTricks RAG). Integrado con homelab personal (Tailscale, segmentación de red).

`Bash` `Python` `Nmap` `ffuf` `Ollama` `RAG`

---

## Proyectos backend (privados)

> Desarrollo también herramientas propias de backend para gestionar mi homelab — no públicas por ahora, pero activas y en uso diario.

- **ha-home-panel** — panel centralizado en Flask que unifica servicios autoalojados (inventario, Home Assistant, monitorización, estado de servicios) detrás de una única API interna.
- **ha-pyscript** — automatizaciones en Pyscript para Home Assistant (persianas con calculo de porcentaje en base a la incidendia del sol sobre la ventana y la tempratura exterior, alarma, electrodomésticos tipo lavavajillas radiadores...etc).
- **ha-automation-toolkit** — utilidades y helpers compartidos para automatizaciones de Home Assistant.
- **hass-localtuya** — integración local de dispositivos Tuya en Home Assistant, sin dependencia de nube modificada para integrar un sistema de calculo en base al tiempo de subida y de bajada al mismo tiempo.

---

## Homelab & Infraestructura

> No solo hago pentesting sobre infraestructura ajena — también diseño, aseguro y mantengo la mía propia. Es mi entorno de pruebas para networking, hardening y automatización.

```
Virtualización      → Proxmox VE (host principal)
Firewall / Routing   → OPNsense (segmentación de red, reglas propias)
Automatización       → Home Assistant OS (control de persianas motorizadas vía LocalTuya Personalizado,
                        dashboard Lovelace propio en YAML)
Videovigilancia      → Frigate NVR + cámaras Tapo (go2rtc)
Gestión de secretos  → Vaultwarden autoalojado
DNS / Adblocking     → AdGuard Home
Acceso remoto        → Tailscale (mesh VPN para acceso seguro a servicios internos)
```

Todo el stack corre autoalojado sobre mi propia red doméstica, segmentada y monitorizada, sirviendo también como base de despliegue para el Offensive Recon Framework.

`Proxmox` `OPNsense` `Home Assistant` `Frigate` `Vaultwarden` `AdGuard Home` `Tailscale` `LocalTuya`

---

## Stack técnico

**Security Tools**
```
Burp Suite · Metasploit · Nmap · ffuf · Gobuster · Nikto
Hydra · SQLmap · Wireshark · tshark · Any.run
```

**Languages / Scripting**
```
Python  ████████  Backend (Flask, APIs), offensive scripts, automation, analysis tools
Bash    ███████   Recon pipelines, system automation
C       █████     Fundamentos de sistemas, hardware embebido (ESP32)
C++     ████      Hardware projects (ESP32) -> Flipper Zero Personal (CH40S)
```

**OS & Platforms**
```
Kali Linux / Parrot  ·  Debian  ·  Windows (básico)
Docker  ·  VirtualBox  ·  Proxmox VE  ·  Tailscale VPN
```

**Methodologies**
```
PTES  ·  OWASP Top 10  ·  Kill Chain  ·  Responsible Disclosure
```

---

## Aprendizaje activo

```
[ En curso ]
  → HTB Academy — Penetration Tester Path
  → HTB Academy — Bug Bounty Hunter Path
  → Active Directory + Windows exploitation
  → OSCP preparation

[ Completado recientemente ]
  → Banking trojan analysis + INCIBE-CERT report
  → HTB machines: Kobold, DevArea, Vulnversity, Silentium
  → Authorized pentest (jubaocolmenarviejo.es)
  → SmartHC professional observation (cybersecurity consultancy)
```

---

## Contacto

[![Email](https://img.shields.io/badge/Email-vrtex781@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vrtex781@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/adrian-rodriguez-ortiz/)

---

<div align="center">
<sub>Colmenar Viejo, Madrid · Disponible para prácticas y posiciones junior en España</sub>
</div>
