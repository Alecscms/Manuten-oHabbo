

## 1️⃣ Estrutura de pastas

Você pode organizar assim:

```
pagina-manutencao/
│
├─ index.html             → Página principal de manutenção (HTML)
├─ assets/                → Pasta para arquivos de mídia e CSS/JS
│   ├─ css/
│   │   └─ app.css        → Estilo customizado da página
│   ├─ js/
│   │   └─ app.js         → Scripts customizados (contagem, fotos, troca de fundo)
│   ├─ images/
│   │   ├─ retros/        → Fotos nostálgicas (foto1.png até foto14.png)
│   │   ├─ videoihabi.mp4 → Vídeo da manutenção
│   │   └─ backgrounds/   → Imagens de fundo (dia, noite, amanhecendo, madrugada)
```

## 2️⃣ Funcionalidades do site

* **Contagem regressiva:**

  * Mostra dias, horas, minutos e segundos até a data alvo (5 de janeiro de 2026).
  * Usa **localStorage** para manter a contagem mesmo após atualizar a página.

* **Novidades:**

  * Lista de novidades estática (não se move).
  * Mostra eventos, itens raros, conquistas, economia, mini-games, tutoriais e atualizações.
  * Não tem animações.

* **Fotos nostálgicas:**

  * Mostra imagens uma de cada vez, alternando a cada 5 segundos.
  * As imagens ficam centralizadas e pequenas para não atrapalhar.

* **Vídeo:**

  * Posicionado lado direito (ou central dependendo do layout).
  * Só reproduz vídeo com play, sem download.
  * Abaixo, existe um card de **Informações importantes**, com texto explicativo sobre a manutenção e novidades.

* **Discord:**

  * Botão fixo na parte inferior da página ou próximo ao login staff.
  * Redireciona para o servidor do Discord.

* **Login Staff:**

  * Continua funcionando conforme a sua CMS/Hotel.
  * Modal de login aparece ao clicar no botão “Login Staff”.
  * Este depende do backend da sua CMS. Se usar outro Habbo/CMS, precisa ajustar o formulário e rota de login.

* **Fundo dinâmico:**

  * Muda conforme o horário do dia: madrugada, amanhecer, dia, noite.
  * Troca automaticamente a imagem de fundo sem precisar recarregar.


## 3️⃣ Como subir no GitHub

1. Crie um repositório no GitHub (ex: `pagina-manutencao`).
2. Faça clone ou envie a pasta `pagina-manutencao` para o repositório.
3. Certifique-se de que a estrutura de pastas está igual à explicada acima.
4. O `index.html` será a página principal.
5. Link para download dos assets: você pode colocar dentro da pasta `assets` ou fornecer links externos.
6. GitHub Pages pode hospedar direto: configure na aba **Settings → Pages → Source: main / root**.


💡 **Observações importantes:**

* Não há backend incluso, então o **login staff** só funciona se você conectar à sua CMS/Habbo.
* Todo o resto (contagem, vídeo, imagens, novidades, Discord) funciona independente do servidor.
* A página é totalmente **responsiva** e vai se adaptar a telas diferentes (desktop, mobile).
* Para atualizar textos ou imagens, basta trocar dentro das pastas correspondentes.
