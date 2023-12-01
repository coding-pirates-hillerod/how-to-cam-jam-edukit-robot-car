# How to cam jam edukit robot car
Dette repo er blot tænkt som et sted til at gøre hele setupet med vores CamJam EduKit Robotics sæt nemmere at komme i gang med.

## How to
Her følger en kort beskrivelse af, hvordan man kommer i gang med robotsættet:
1. Klon og setup Raspberry Pi OS
2. Opdater OS
3. Opsæt evt. VNC adgang til din Pi
4. Byg robotten
5. Kod robotten

### Klon og setup Raspberry Pi OS
Brug en SD kort læser til at klone og konfigurere et Raspberry Pi OS.

### Opdater OS
Indsæt micro SD kort i din Pi, ssh ind i den og opdater den vhja følgende kommandoer:

Kør først
```bash
sudo apt update
```

Kør derefter

```bash
sudo apt upgrade -y
```

### Opsæt evt. VNC adgang til din Pi
Hvis man synes det er nemmest at kode sin robot via "Remote Desktop", så hent først denne VNC viewer: https://www.realvnc.com/en/connect/download/viewer/

Opsæt derefter din Pi til at håndtere VNC gennem "raspi-config", dvs. kør denne kommando for at sætte det op:

```bash
sudo raspi-config
```

Reboot herefter din Pi og brug VNC viewer til at få "Remote Desktop" adgang. For at reboote, så kør:
```bash
sudo reboot
```

### Byg din robot
Følg vejledningerne til at bygge din robot vhja dette repo: https://github.com/CamJam-EduKit/EduKit3

### Kode robotten
