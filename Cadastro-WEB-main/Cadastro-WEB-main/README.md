# Cadastro de Usuários

## 1. Introdução
O sistema de Cadastro de Usuários tem como objetivo permitir o registro e gerenciamento de informações de usuários de forma simples e eficiente.  
Esta é a FASE 1 do projeto, focada em Frontend e Documentação.  
A FASE 2 incluirá a integração com Flask (Python) e SQLite (banco de dados).

---

## 2. Objetivos

### Objetivo Geral
Desenvolver um sistema funcional de cadastro de usuários, contendo validação de dados e interface amigável, além de documentar seus requisitos e diagramas.

### Objetivos Específicos
- Criar uma interface de cadastro funcional e intuitiva.  
- Corrigir erros existentes no protótipo original.  
- Propor melhorias e adicionar novos campos ao formulário.  
- Elaborar a documentação técnica (requisitos e diagramas).  

---

## 3. Tecnologias Utilizadas
- HTML5 – Estrutura das páginas  
- CSS3 – Estilização e layout responsivo  
- JavaScript – Validação e interatividade  
- (Fase 2) Flask (Python) e SQLite – Backend e banco de dados  

---

## 4. Requisitos do Sistema

### 4.1 Requisitos Funcionais (RF)
| Código | Descrição |
|:--|:--|
| RF01 | O sistema deve permitir o cadastro de usuários. |
| RF02 | O sistema deve validar campos obrigatórios antes do envio. |
| RF03 | O sistema deve exibir mensagens de sucesso ou erro após o envio. |
| RF04 | O sistema deve permitir a visualização dos dados cadastrados. |
| RF05 | O sistema deve permitir a edição de informações do usuário. |
| RF06 | O sistema deve permitir a exclusão de um usuário cadastrado. |

### 4.2 Requisitos Não Funcionais (RNF)
| Código | Descrição |
|:--|:--|
| RNF01 | O sistema deve ser desenvolvido em HTML, CSS e JavaScript. |
| RNF02 | O sistema deve apresentar um design responsivo. |
| RNF03 | O carregamento da página não deve ultrapassar 3 segundos. |
| RNF04 | O código deve ser compatível com navegadores modernos (Chrome, Edge, Firefox). |
| RNF05 | O sistema deve ter uma interface intuitiva e de fácil navegação. |

---

## 5. Diagrama Entidade-Relacionamento (DER)

Entidade: `Usuario`  
Atributos:
- id_usuario (PK)  
- nome  
- email  
- senha  
- confirmar_senha  
- cpf  
- data_nascimento  
- telefone  
- endereco  
- cidade  
- estado  
- cep  

O DER representa uma única entidade principal (Usuário).  
Em versões futuras, poderão ser adicionadas novas entidades, como Perfil ou Permissão.

---

## 6. Diagrama de Caso de Uso

Ator Principal: Usuário  

Casos de Uso:
1. Cadastrar usuário  
2. Validar dados do formulário  
3. Editar informações do usuário  
4. Excluir usuário  
5. Visualizar lista de usuários  

O diagrama representa o ator "Usuário" interagindo com estes casos de uso.  
Pode ser criado em ferramentas como Lucidchart, Draw.io ou diagrams.net.

---

## 7. Melhorias Propostas

### Campos adicionados
- CPF  
- Data de nascimento  
- Telefone  
- Endereço (Rua, Cidade, Estado, CEP)  
- Confirmação de senha  

### Melhorias visuais
- Layout responsivo  
- Mensagens de feedback (erros e sucesso)  
- Botão de "Limpar Campos"  
- Indicação de campos obrigatórios  

---

## 8. Cronograma de Entregas

| Etapa | Descrição | Data |
|:--|:--|:--:|
| Fase 1 | Documentação e Frontend | 06/11 |
| Fase 2 | Backend (Flask) + Banco de Dados (SQLite) | 13/11 |

---

## 9. Conclusão
A primeira fase do projeto foi dedicada à construção do frontend e à documentação técnica.  
O protótipo de cadastro de usuários foi aprimorado com novos campos e validações, proporcionando uma experiência mais completa.  
A próxima etapa será integrar o backend desenvolvido em Flask e o banco de dados SQLite, completando o funcionamento do sistema.

---

## Autores
- Pedro Lucas Miranda Teles
- Kauan Lindolfo
