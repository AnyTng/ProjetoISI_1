# Como executar isto

## 1) Instalar o Knime

1. [Aqui](https://www.knime.com/downloads)

## 2) Chave da API do OpenAQ

1. [Cria uma conta no OpenAQ e gera uma API Key.](https://explore.openaq.org/register)  
2. Substitui o valor de `X-API-KEY` em **todos** os nós de *GET request*.

---

## 3) Instalar e executar o Node-RED

**macOS / Linux (npm):**
~~~bash
sudo npm install -g --unsafe-perm node-red
node-red
~~~

**Windows (npm):**
~~~cmd
npm install -g --unsafe-perm node-red
node-red
~~~

Depois abre o editor em: [http://localhost:1880](http://localhost:1880)

---

## 4) Instalar o *add-on* de *dashboard* do Node-RED

No editor:  
**Menu → Manage Palette → Install** e procura por:
- `@flowfuse/node-red-dashboard`

A *Dashboard* fica em: [http://localhost:1880/dashboard](http://localhost:1880/dashboard)

---

## 5) Escolher o caminho dos logs (ficheiros) — KNIME

Em cada nó que escreve ficheiros (*CSV/JSON Writer*), define o caminho onde queres guardar os logs.  
Exemplo:
- **macOS/Linux:** `/Users/<o_teu_utilizador>/Projetos/openaq/logs/`
- **Windows:** `C:\Users\<o_teu_utilizador>\Projetos\openaq\logs\`

## 6) Executar a workflow no botão do Knime
  
