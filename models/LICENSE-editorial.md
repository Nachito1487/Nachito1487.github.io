# ABCuerpo — modelo corporal propuesto

Fecha de preparación: 14/10/2026. No es un modelo clínico ni constituye validación profesional.

## Procedencia y licencia

Base anatómica y rig: MakeHuman/MPFB, preparada y distribuida por Innerscene como «Human base mesh with editable 53-bone rig».
https://www.innerscene.com/tools/library/3d-parts/human-base-mesh-with-editable-53-bone-rig-8e7c8ab1
Archivo original: human-base-rigged.glb. La página de origen dedica el conjunto a CC0 y permite uso, modificación y redistribución comercial.

Piel y complementos de rostro/cabello: personaje Avery de «Relaxed stance - 3D Person, Standing», adaptado por Innerscene de MakeHuman y distribuido bajo CC0.
https://www.innerscene.com/tools/library/3d-parts/relaxed-stance-3d-person-standing-139755ea
Archivo original: standing-relaxed.glb. El material de piel identifica a Jartur/jartur69 en el nombre de textura; cejas, pestañas, ojos, dientes y short04 proceden del paquete MakeHuman incluido por el distribuidor.

CC0: https://creativecommons.org/publicdomain/zero/1.0/
Licencia de assets MakeHuman: https://github.com/makehumancommunity/makehuman/blob/master/LICENSE.md
La licencia del software MakeHuman (AGPL) es distinta de la dedicación CC0 de estos assets. No se incorpora código de MakeHuman a la web.

## Adaptación ABCuerpo

Se conservó la geometría base en postura estática. Se incorporaron la textura de piel, cejas, pestañas, ojos, dientes y cabello del mismo personaje fuente, ajustando su posición al cuello/cabeza de la base. Se eliminaron animaciones y rig para reducir carga. Se redujeron y comprimieron texturas, sin generar piel con IA.

Se dividió la malla por materiales para resaltar pies, manos y región facial. Los pies incluyen ambas superficies completas hasta el límite del tobillo; se interpolaron cortes para evitar bordes dentados. Manos y cara usan máscaras geométricas aproximadas, no límites diagnósticos. El pantalón corto es un material navy aplicado a la zona cubierta, no una simulación textil independiente.

Los originales se conservan en scripts/assets para reproducir la preparación con scripts/build-body-model.py. Archivo de uso web: body-editorial.glb. Los nombres comerciales de los autores no implican patrocinio ni aval de ABCuerpo.
