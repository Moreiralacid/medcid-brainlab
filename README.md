# MEDCID - BRAINLAB

Aplicativo web instalável em formato PWA para acompanhar hábitos, padrões, crenças, estudos, revisões, saúde, igreja e relatórios.

## Como abrir localmente

1. Extraia o ZIP.
2. Abra a pasta `medcid_brainlab_pwa`.
3. Abra o arquivo `index.html` no navegador.

## Como testar como PWA no computador

O PWA funciona melhor em HTTPS ou localhost. Para testar localmente, abra o terminal dentro da pasta e rode:

```bash
python -m http.server 8000
```

Depois abra:

```text
http://localhost:8000
```

## Como instalar no Android

1. Hospede a pasta em um serviço com HTTPS, como GitHub Pages, Netlify ou Vercel.
2. Abra o link no Chrome.
3. Toque no menu de três pontos.
4. Escolha **Instalar app** ou **Adicionar à tela inicial**.
5. Confirme.

## Como instalar no iPhone

1. Hospede a pasta em um serviço com HTTPS, como GitHub Pages, Netlify ou Vercel.
2. Abra o link no Safari.
3. Toque em **Compartilhar**.
4. Escolha **Adicionar à Tela de Início**.
5. Confirme o nome **MEDCID - BRAINLAB**.

## Arquivos PWA adicionados

- `manifest.json`
- `service-worker.js`
- `icons/icon-192.png`
- `icons/icon-512.png`

## Recursos

- Central diária com XP e missão principal.
- Flashtest digital 0–100 com classificação automática.
- Jornada de 9 módulos com progresso e anotações.
- Missões diárias e modo recuperação.
- Mapa de padrões: gatilho, custo, substituição e ação mínima.
- Crenças automáticas e declarações funcionais.
- Blindagem digital, física e espiritual.
- Estudos médicos, questões e revisões D+1, D+3, D+7, D+15 e D+30.
- Saúde, devocional, serviço e limites.
- Relatórios semanais com gráficos.
- Exportação/importação de backup JSON.
- Instalação como PWA no Android/iPhone.

## Importante

Os dados ficam salvos no navegador usando `localStorage`. Exporte backup JSON antes de limpar histórico/cache, trocar de aparelho ou reinstalar o app.
