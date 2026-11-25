# Formação Sem Barreiras

Plataforma web que prepara pessoas com deficiência para o mercado de trabalho, com cursos interativos, simulação de entrevistas e recursos de acessibilidade integrados.

> Projeto em grupo desenvolvido em 2025 durante o curso técnico em Análise e Desenvolvimento de Sistemas (Senai Diadema).

## Funcionalidades

- **Cursos interativos** com vídeo e quiz de múltipla escolha (ex.: "Primeiro Emprego"), barra de progresso e resultado final com diagnóstico e recomendações.
- **Pausar e retomar:** o progresso do curso é salvo na conta do usuário.
- **Simulação de entrevistas**, jogos e **histórico** de resultados.
- **Login e cadastro** com preferências de acessibilidade.
- **Área administrativa** restrita a administradores.
- **Menu de acessibilidade:**
  - aumentar e diminuir fonte, fonte legível e espaçamento entre letras;
  - alto contraste escuro e inversão de cores;
  - modos para daltonismo (protanopia e deuteranopia);
  - destaque de links e cabeçalhos;
  - guia de leitura e linhas de leitura.
- **Tradução para Libras** com o plugin [VLibras](https://vlibras.gov.br/).

## Tecnologias

- HTML, CSS e JavaScript
- Firebase (Authentication e Firestore)
- VLibras

## Como rodar localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/gustavo13579/formacao-sem-barreiras.git
   ```

2. Abra a pasta e execute o arquivo `index.html` no navegador (ou use uma extensão como o Live Server do VS Code).
3. O login e o salvamento de resultados usam o Firebase. Para usar o seu próprio projeto, crie um no [Firebase Console](https://console.firebase.google.com/), ative **Authentication (e-mail/senha)** e **Firestore**, e troque o objeto `firebaseConfig` nos arquivos HTML.

## Estrutura

```
index.html        página inicial, cadastro e login
cursos.html       lista de cursos
curso1.html ...   cursos com quiz
simulador.html    simulação de entrevista
jogos.html        jogos
historico.html    histórico de resultados
admin.html        área administrativa
img/ videos/      imagens e vídeos
```


## Equipe

- Gustavo Santos de Barros: cursos e questionários
- Victor Costa Diniz: jogos
- Maria Clara Ribeiro Magalhães: Firebase, login e histórico
- Gabrielle Silva Santa Rosa: login, página principal e acessibilidade

## Contato

[LinkedIn](https://www.linkedin.com/in/gustavo-santos-de-barros/) • gustavosantosdebarros1@gmail.com
