# JCPLAN — Escavadeira alinhada ao caminhão

Ajuste feito: `src/components/Hero.astro`

## O que foi corrigido
- A escavadeira agora anda na mesma reta visual do caminhão.
- O deslocamento continua horizontal, sem desalinhar da base do caminhão.
- Removidos estilos antigos de `data-position` que podiam conflitar com o movimento contínuo.

## Instalação
```bash
cd ~/development/terraplanagem-jcplan-site
unzip -o ~/Downloads/jcplan-escavadeira-alinhada-caminhao.zip -d .
npm run dev
```
