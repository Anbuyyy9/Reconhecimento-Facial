# 🧠 Reconhecimento Facial com Azure Cognitive Services

Este projeto demonstra o uso dos serviços cognitivos da Microsoft Azure para realizar **reconhecimento facial** em imagens. A aplicação identifica rostos humanos em fotos e gera informações detalhadas sobre cada rosto detectado.

---

## 📁 Estrutura do Projeto

```
Reconhecimento-Facial/
├── INPUT/
│   ├── Dinosaurros.jpg
│   ├── descoberta-dos-indios-1805778318.png
│   └── familia-um-lugar.jpg
├── OUTPUT/
│   ├── DANOSAURROS.txt
│   ├── INDIOS.txt
│   └── Rosto nº 1 FAMILIA.txt
└── README.md
```

---

## 📌 Descrição

- As imagens são armazenadas na pasta `INPUT/`.
- O reconhecimento facial é realizado com a **API Face do Azure Cognitive Services**.
- Os resultados (como atributos faciais, emoções e posição dos rostos) são exportados em arquivos `.txt` na pasta `OUTPUT/`.

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Azure Cognitive Services – Face API**
- **Python 3.x**
- Bibliotecas auxiliares:
  - `requests` – comunicação com a API do Azure
  - `os` – manipulação de arquivos locais
  - `json` – tratamento de respostas da API

---

## 🚀 Como Usar

1. Configure sua **chave de API** e **endpoint** no portal do Azure (Face API).
2. Adicione suas imagens na pasta `INPUT/`.
3. Edite o script Python com sua chave e endpoint.
4. Execute o script.
5. A saída será gerada automaticamente na pasta `OUTPUT/`.

---

## 📄 Exemplo de Saída

### Entrada:
📷 `familia-um-lugar.jpg`

### Saída:
📝 `Rosto nº 1 FAMILIA.txt` com dados como

---

## ✅ Funcionalidades

- [x] Detecção de rostos em imagens
- [x] Extração de características faciais
- [x] Geração de relatórios automáticos (.txt)
- [x] Suporte a múltiplas imagens na entrada

---

## 👤 Autor

- Gabriel ([@Anbuyyy9](https://github.com/Anbuyyy9))

---

## 📌 Observações

- Se nenhuma face for detectada, o arquivo `.txt` correspondente indicará a ausência de rostos.
- Esse projeto é uma **atividade prática educacional** sobre uso de IA na nuvem com **Microsoft Azure**.

---

## 🧠 Aprendizados

- Integração com **Azure AI Cognitive Services**
- Processamento e reconhecimento facial com Python
- Geração dinâmica de relatórios com informações extraídas via API
- Manipulação de arquivos em lote para automação
