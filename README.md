#  Ferramenta de Compactação e Descompactação 'extrator_insersor_wad_app_bin' - by Lobo Nintendista

🚀 # Transforme seus arquivos .wad, .app e .bin facilmente

Esta ferramenta foi desenvolvida para a comunidade Wii, permitindo compactar e descompactar arquivos `.wad`, `.app` e `.bin` de forma simples e rápida, utilizando binários poderosos como `libWiiSharp.dll`, de **leathl**. Ideal para quem trabalha com arquivos de jogos, mods ou emuladores do Nintendo Wii, especialmente para quem deseja organizar ou modificar o conteúdo desses arquivos.

## O que é?

Com a ferramenta, você pode:

- Descompactar arquivos nos formatos `.wad`, `.app` ou `.bin`.
- Compactar diretórios em novos arquivos `.wad`, `.app` ou `.bin`.

A interface é simples e direta, com um toque divertido da pequena propaganda no título da janela, assinada por **Lobo Nintendista**.

## Como Funciona?

1. Arraste e solte um arquivo `.wad`, `.app` ou `.bin` sobre o executável da aplicação.
2. A ferramenta descompactará automaticamente o arquivo, criando uma pasta com o conteúdo extraído.
3. Caso arraste um diretório com sufixo `_wad`, `_app` ou `_bin`, o diretório será compactado no formato correspondente.
4. Receba mensagens informativas sobre o status de cada operação.

### Funcionalidades

#### Descompactação
- **.wad** → Arquivos WAD.
- **.app** → Arquivos U8.
- **.bin** → Arquivos U8.

#### Compactação
- Diretórios com sufixos `_wad`, `_app` ou `_bin` serão compactados nos formatos respectivos.

**Exemplos:**

- Arraste um arquivo `.wad`: ele será descompactado, extraindo o conteúdo do arquivo WAD.
- Arraste um diretório com o nome `_wad`: ele será compactado de volta em um arquivo `.wad`.

## Como Usar?

### Pré-requisitos
- **Windows**
- Biblioteca `libWiiSharp.dll` (embutida no programa)

### Passos

1. Baixe o repositório e compile o código ou utilize o executável já compilado.
2. Arraste e solte o arquivo desejado na aplicação.
3. A ferramenta cuidará da compactação/descompactação automaticamente.
4. Aplique as modificações e aproveite!

### Exemplo de Execução

- **Descompactar um arquivo WAD:**  
  Arraste e solte o arquivo `.wad`. O conteúdo será extraído na mesma pasta.

- **Compactar uma pasta:**  
  Renomeie a pasta para algo como `meu_mod_wad` e arraste para a aplicação. O arquivo `.wad` será gerado com sucesso.

### Mensagens e Feedback Visual
- Notificações após cada operação garantem que você saiba o que está acontecendo.
- Textos personalizados incluem a assinatura de **Lobo Nintendista** em cada título de mensagem.

## Tecnologias Utilizadas

- **C**: Linguagem principal da aplicação.
- **Windows API**: Para a criação de janelas e caixas de mensagens.
- **Binários**: `libWiiSharp.dll` para manipulação dos arquivos (já embutido no programa).

## Contribuições

Se você tem sugestões, melhorias ou correções, fique à vontade para abrir uma **issue** ou um **pull request**. Agradecemos muito sua ajuda para tornar esta ferramenta ainda mais útil!

🌟 **By Lobo Nintendista - Dedicado à comunidade Wii** 🌟


