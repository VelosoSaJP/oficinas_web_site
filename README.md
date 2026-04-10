# ./inventário

Site de apresentação do projeto **./inventário** — Sistema Automatizado de Controle de Estoque com RFID.

Desenvolvido para a disciplina de **Oficina de Integração 2** do curso de Engenharia de Computação da **UTFPR** (2026), sob orientação dos professores César M. Vargas Benítez e Daniel Rossato.

## Sobre o projeto

O ./inventário resolve o problema do controle manual de estoque em pequenos negócios, combinando leitura RFID e medição por peso para automatizar o inventário em tempo real. O hardware utiliza ESP32 + leitor RC522 + célula de carga HX711, e o pagamento é integrado via Pix com a API do Mercado Pago.

## Links

- [Site hospedado no Vercel](https://oficinas-web-site.vercel.app/)

## Equipe

| Nome | Papel |
| :--- | :---- |
| Enzo Westphal Tacla | Documentação & Integração |
| Felipe Dias Peixoto | Hardware & Firmware |
| João Pedro Veloso | Frontend & Backend |

## Estrutura do site

```text
src/
├── layouts/
│   └── Layout.astro       # Layout base com Navbar e Footer
├── components/
│   ├── Navbar.astro
│   └── Footer.astro
└── pages/
    ├── index.astro         # Página inicial (hero + destaques)
    ├── sobre.astro         # Contexto, motivação, objetivos e metodologia
    ├── equipe.astro        # Membros da equipe
    ├── funcionalidades.astro  # Funcionalidades do sistema
    ├── resultados.astro    # Métricas, screenshots e demo
    └── contato.astro       # Links do projeto e contatos
```

## Comandos

| Comando           | Ação                                        |
| :---------------- | :------------------------------------------ |
| `npm install`     | Instala as dependências                     |
| `npm run dev`     | Inicia o servidor local em `localhost:4321` |
| `npm run build`   | Gera o build de produção em `./dist/`       |
| `npm run preview` | Visualiza o build antes de publicar         |

