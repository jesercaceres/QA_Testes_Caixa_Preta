![Selenium.jpg](https://res.cloudinary.com/damien1/w_800,c_scale,f_auto,q_auto,dpr_3.0/blog/selenium_logo.png)

# Teste de Interface de Login

Este projeto envolve a criação de testes automatizados para avaliar a tela de login do Facebook. Nos testes foram abordados aspectos como segurança, usabilidade e desempenho.

## Facebook


O [Facebook](https://www.facebook.com/) é uma rede social online que permite aos usuários criar perfis pessoais, compartilhar fotos e vídeos, enviar mensagens e manter contato com amigos, família e colegas de trabalho. 

## Pré-requisitos

Para a produção e execução dos testes, utilizei o software [Selenium WebDriver](https://www.selenium.dev/).

Arquivos no repositório:

- `Facebook LOGIN Testes.side`: Arquivo contendo testes para abrir no Selenium.
- `Caixa preta, Facebook.xlsx`: Planilha com cada cenário de teste detalhado.

## Instalação

Para executar os testes, você precisa instalar o Selenium e acessa-lo pelo Chrome. 

1. Instalação [Selenium](https://chromewebstore.google.com/?hl=pt-BR)

## Executando os Testes

Os testes realizados na tela de login cobriram diversos cenários cruciais. Listei alguns dos cases abaixo, porém você pode consultar todos os testes que foram abordados através desta [Planilha testes de caixa preta](https://docs.google.com/spreadsheets/d/1-nw1zTSxbjiAU5NxnhH-2lu4vAtJ_T8Z9km85RvTVHg/edit?usp=sharing)

- **Validação de E-mail/Telefone**: Verificação de formatos válidos e inválidos, incluindo o teste de entradas com espaços e caracteres especiais.
- **Validação de Senha**: Teste de senhas válidas e inválidas, considerando diferentes níveis de complexidade, uso de caracteres especiais, e sensibilidade a maiúsculas e minúsculas.
- **Campos Vazios**: Testes para garantir que a tentativa de login com campos vazios seja adequadamente bloqueada com mensagens de erro claras.
- **Mensagens de Erro**: Verificação das mensagens de erro exibidas para garantir que estão claras e precisas para cada tipo de falha de validação.
- **Recuperação de Senha**: Testes de funcionalidade de recuperação de senha usando e-mail e telefone válidos, incluindo cenários com dados não cadastrados.
- **Bloqueio de Usuário**: Teste para verificar o bloqueio de acesso após tentativas de login consecutivas com credenciais incorretas.
- **Sessão e Logout**: Verificação do manejo adequado de sessões, incluindo testes de logout para garantir o encerramento seguro da sessão.
- **Resistência a Ataques**: Testes de resistência a ataques comuns como injeção de HTML e força bruta.

## Registro de teste

[Vídeo Teste de Caixa Preta - Facebook](https://youtu.be/DwBUts8UAXU)

## Autor

Jéser Cáceres Marcelino `RA: 224044`
