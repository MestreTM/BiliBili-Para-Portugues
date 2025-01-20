
# BiliBili Para Português
![image](https://i.imgur.com/nqK35FN.png)

## Descrição

BiliBili Para Português é uma extensão de navegador que traduz automaticamente o conteúdo do site BiliBili para o português. Baseado no [BiliBili-To-English](https://github.com/LazyScar/BiliBili-To-English) feito pelo LazyScar.

## Funcionalidades

- Tradução automática do conteúdo do BiliBili para o português.
- Compatível com textos dinâmicos e placeholders.
- Sistema de cache para acelerar traduções.
- Atualizações automáticas para novos elementos adicionados à página.

## Como Instalar

1. Baixe ou clone este repositório no seu computador:
   ```bash
   git clone https://github.com/seu-usuario/bilibili-para-portugues.git
   ```
2. Acesse as configurações de extensões do seu navegador:
   - **Chrome:** `chrome://extensions/`
   - **Edge:** `edge://extensions/`
3. Ative o **Modo de Desenvolvedor**.
4. Clique em **Carregar sem compactação** e selecione a pasta do repositório baixado.
5. A extensão será adicionada ao navegador.

## Arquivos Principais

- `manifest.json`: Configuração da extensão.
- `dictionary.js`: Contém os mapeamentos para tradução de palavras-chave.
- `main.js`: Código principal que gerencia as traduções e interações com o site.
- Ícones: Imagens para personalizar a extensão na barra do navegador.

## Permissões Necessárias

A extensão requer as seguintes permissões:
- **activeTab**: Para acessar e manipular o conteúdo da aba ativa.
- **storage**: Para armazenar traduções em cache local.
- **host_permissions**: Acessar as páginas do domínio `bilibili.com`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

**Nota:** Este projeto não é afiliado ou patrocinado pela BiliBili.
