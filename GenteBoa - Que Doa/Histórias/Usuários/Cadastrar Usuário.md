## História: Cadastrar Usuário

### Descrição da História:

**COMO** usuário não cadastrado  
**QUERO** me cadastrar no sistema  
**PARA** acessar o sistema

### Critérios de Aceitação da História:

- Nome de usuário deve ser único e obrigatório, e possuir:
 - no mínimo 8 caracteres;
 - somente caracteres alfanuméricos;
- Senha deve possuir:
 - no mínimo 8 caracteres;
 - no mínimo um caractere alfabético;
 - no mínimo um caractere numérico;
 - no mínimo um caractere especial.
- ~Foto pessoal obrigatória;~
- Nome completo obrigatório;

### Critérios de Produto:

- O sistema informará com erro em caso algum campo obrigatório não preenchido;
- O sistema informará com erro em caso algum campo inválido;
- O sistema informará com erro em caso de usuário já cadastrado;
- O sistema informará com sucesso em caso de submissão de dados corretos;
- O sistema autenticará automaticamente o usuário após o cadastro com sucesso.