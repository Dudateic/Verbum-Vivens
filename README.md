🌿 Verbum - Poemas e Poesias

**Verbum** é um visualizador interativo de poemas e poesias com interface limpa e animações leves. Ele permite buscar poemas de uma API em inglês ou carregar conteúdos locais (poemas.json e poesias.json), além de exportar e copiar os textos.

---

🚀 Como Usar

1. **Abra o arquivo** `index.html` no navegador.
2. Selecione a **fonte**:
   - **API (Inglês)** – busca poemas aleatórios online.
   - **Poemas** – utiliza o arquivo local `poemas.json`.
   - **Poesias** – utiliza o arquivo local `poesias.json`.
3. Escolha o **modo**:
   - **Aleatório** – seleciona um poema ao acaso.
   - **Específico** – permite escolher um poema da lista.
4. Clique em **"🎲 Carregar"** para exibir o poema.
5. Use os botões:
   - **📋 Copiar**: copia o poema para a área de transferência.
   - **📄 Exportar TXT**: salva o poema como um arquivo `.txt`.

---

📁 Estrutura dos Arquivos JSON

`poemas.json` ou `poesias.json`

```json
{
  "poemas": [
    {
      "titulo": "A Canção da Floresta",
      "autor": "João Silva",
      "texto": "Nas sombras verdes canta o vento..."
    },
    ...
  ]
}
```

🔖 Cada item contém:
- **titulo**: Título do poema/poesia.
- **autor**: Nome do autor.
- **texto**: Corpo completo da obra.

---

🎨 Extras

- Animações suaves de folhas caindo (CSS + JavaScript).
- Interface responsiva para dispositivos móveis.
- Suporte a acessibilidade com uso de ARIA e navegação por teclado.

---

📤 Exportações Disponíveis

- **Copiar poema**: botão "📋 Copiar"
- **Salvar como TXT**: botão "📄 Exportar TXT"
- *(Suporte a exportar PDF pode ser adicionado futuramente)*

---

📌 Requisitos

- Navegador moderno (Chrome, Firefox, Edge ou Safari).
- Conexão com a internet para usar a API (opcional).

---

📝 Licença

Este projeto é de uso livre para fins educacionais e culturais.
