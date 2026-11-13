# Connector7 a macOS

Hi ha dues versions, cadascuna a la seva Release:

| Versió | Per a quin Mac | Eines de compilació |
|---|---|---|
| Apple Silicon (arm64) | Macs amb xip Apple (M1 o posterior) | Incloses a l'app; compila sense connexió |
| Intel (x86_64) | Macs Intel; en Apple Silicon funciona amb Rosetta 2 | Es baixen la primera vegada que es fan servir |

- Totes dues requereixen macOS 12 o posterior.
- Signatura ad-hoc, sense notarització: el primer cop obriu l'app amb clic dret > Obre.
- Si passeu de la versió Intel a la d'Apple Silicon en el mateix Mac, esborreu abans la carpeta
  `~/Library/Application Support/STEAMakersBlocks/Connector7/toolchains`; si no, l'app mostrarà
  l'error "Rosetta is forbidden".
