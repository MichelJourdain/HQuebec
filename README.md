# HQuébec

### Installation

- Intallez [Hydroqc Add-on](https://hydroqc.ca/fr/docs/installation/hass-addon/)
- Intallez [Tabbed-card](https://github.com/kinghat/tabbed-card) [HACS] 
- Intallez [Layout-card](https://github.com/thomasloven/lovelace-layout-card) [HACS]
- Intallez [Mushroom card](https://github.com/piitaya/lovelace-mushroom) [HACS]
- Intallez [Flex-horseshoe-card](https://github.com/AmoebeLabs/flex-horseshoe-card) [HACS]
- Intallez [Apexcharts-card](https://github.com/RomRider/apexcharts-card) [HACS]
- Intallez [Card_mod](https://github.com/thomasloven/lovelace-card-mod) [HACS]
- Copiez Sous-Vue-Hydro-Quebec.yaml
- Copiez le répertoire Cates.
- Copiez le répetoire Package.

### Thème

Si vous êtes intéressé par le theme LCARS, vous pouvez l'utilser. Mais il n'est pas essentiel. 

- [Thème LACRS](https://github.com/th3jesta/ha-lcars)

Si vous n'utilisez pas le thème, vous pouvez retiré tout les markdown du code.
Vous pouvez aussi retiré les card_mod qui ne contiennent que du code nécessaire pour le thème.

EX:
```
            - type: markdown
              content: "# Hydro-Québec Maison"
              card_mod:
                class: header-contained

            - type: custom:apexcharts-card
              card_mod:          ------> À retirer
                class: middle-contained      ------> À retirer

```  

- Restart Home Assistant

## Screenshots

![image](https://github.com/MichelJourdain/HQuebec/assets/83040228/61b34fc9-95e9-4109-af1e-7c697f4cfcbf)

![image](https://github.com/MichelJourdain/HQuebec/assets/83040228/d0a28268-9213-43d1-b88d-1b08794e4103)

![image](https://github.com/MichelJourdain/HQuebec/assets/83040228/e0171e6c-7fc8-401c-b78c-734ceaae1511)

### Changelog
#### 1.0
- First release

