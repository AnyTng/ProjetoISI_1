# Como executar isto

## 1) Chave da API do OpenAQ

1. [Cria uma conta no OpenAQ e gera uma API Key.](https://explore.openaq.org/register)
2. Substitui o valor da X-API-KEY presente em todos os nós de Get request

---

## 2) Instalar e executar Node-RED 

```bash
# macOS/Linux (via npm)
sudo npm install -g --unsafe-perm node-red
node-red
```cmd
# Windows
npm install -g --unsafe-perm node-red
node-red


Depois abre o editor em: http://localhost:1880

---

## 3) Instalar o *add-on* de *dashboard* do Node-RED

- Pelo menu do editor: **Menu → Manage Palette → Install** e procura por:
  - `@flowfuse/node-red-dashboard` 


A Dashboard está em `http://localhost:1880/dashboard`.


## 4) Escolher o caminho dos logs (ficheiros) — KNIME

Define, para cada nó que escreve ficheiros (CSV/JSON Writer), o caminho onde armazenar os Logs

