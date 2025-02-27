# ClamAV
ClamAv_Usage

## Installation:
```sudo apt update && sudo apt install clamav -y```

## Mis à jour des signatures:
```sudo freshclam```

## Scanner un dossier spécifique :
```clamscan -r /home/user/Documents```

## Scanner et supprimer les fichiers infectés automatiquement :
```clamscan -r --remove=yes /home/user/Documents```

## Vérifier si freshclam tourne avec systemd:
```sudo systemctl start clamav-freshclam```
```sudo systemctl restart clamav-freshclam```
```sudo freshclam```

