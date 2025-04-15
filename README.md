# Blog Django - Projeto ES

Este é um projeto de blog desenvolvido com Python e Django. O blog tem como principal funcionalidade a exibição de postagens.

## Informações do Projeto

- **Universidade**: UNIVESIDADE FEDERAL DO TOCANTINS
- **Curso**: CIENCIAS DA COMPUTACAO
- **Disciplina**: ENGENHARIA DE SOFTWARE
- **Semestre**: 2025/01
- **Professor**: Edeilson Milhomem da Silva
- **Equipe**: Jonata Rubens Silva Araujo, Afonso Dglan Cirqueira Rodrigues, Carlos Eduardo Ribeiro Lima, Marcus Vinicius Guimaraes Balbino

## Tecnologias Utilizadas

- Python 3.x
- Django (versão mais recente)
- HTML, CSS e Bootstrap (para estilização)

## Funcionalidades

- Exibir postagens publicadas
- Interface responsiva

# 📝 Blog Simples em Django

Um projeto de blog desenvolvido com Django, focado no aprendizado do fluxo de trabalho com Git. O sistema permite a listagem de posts e visualização do conteúdo individual de cada post.

## Link de apresentação do projeto 
https://drive.google.com/file/d/1dQ_q6OmaJ9FaRwnBxY6qHksmmMfuccFr/view?us
p=drive_link

---
## 🧩 User Story

**Como** visitante do blog,  
**Quero** visualizar uma lista de posts disponíveis,  
**Para** poder clicar em um post e acessar seu conteúdo completo em uma página separada.

---

## 📌 Divisão de Tarefas (Splits)

1. **Configuração inicial**
   - Criação do ambiente virtual (venv)
   - Configuração básica do projeto Django
   - Criação da rota inicial com página em branco![image](https://github.com/user-attachments/assets/b9d78358-624f-4862-894d-877e10d0f857)


2. **Criação do modelo de Post**
   - Definição da estrutura do modelo no Django
   - Migração para criação da tabela no banco de dados
   - Inserção de posts fictícios para testes

3. **Estilização**
   - Aplicação de estilos básicos com CSS
   - Ajustes visuais simples para melhor apresentação

4. **Criação da Navbar e Rodapé**
   - Implementação da barra de navegação
   - Inclusão de rodapé padrão no layout

---

## ℹ️ Observação

A estrutura do projeto foi propositalmente mantida **simples e direta**, visando facilitar o entendimento do **fluxo de versionamento com Git**. Isso se deu especialmente pela limitação de alguns membros da equipe em relação ao uso da ferramenta, priorizando a prática colaborativa em um ambiente acessível.

---

## 🚀 Instalação

```bash
git clone https://github.com/JonataRubens/BlogDeNoticias
cd nome-do-repo
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

## Licença

Este projeto está sob a licença MIT.

