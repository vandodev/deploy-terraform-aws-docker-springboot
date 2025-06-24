<h3 align="center">
  Deploy com Terraform, AWS, Docker e SpringBoot
</h3>

Lista de tarefas

Aplicação java
- [x] Iniciando projeto java
- [x] Configurando endpoint básico
- [x] Publicando nosso app java dentro do container (docker)
- [x] Testando nosso container de app java

Infraestrutura básica
- [ ] Iniciando o projeto de infraestrutura (terraform init)
- [ ] Criando usuário para acesso programático na aws
- [ ] Configurando as credenciais via aws cli
- [ ] configurando o servidor EC2 na aws via Terraform
- [ ] Permitindo acesso HTTP no servidor
- [ ] Configurando o script de inicialização  do servidor -> user_data.sh
- [ ] realizar a criação da infra via terraform (terraform apply)
- [ ] testar a api

Infra estrutura com acesso remoto
- [ ] Configurando nosso KeyPair para acesso SSH (ssh-keygen)
- [ ] Criando o KeyPair na aws via terraform
- [ ] Permitindo o acesso SSH no servidor
- [ ] realizando a atualização da infra via terraform (terraform apply)
- [ ] testando a api e o acesso remoto

Limpeza do ambiente
- [ ] Realizar a destruição da infraestrutura criada (terraform destroy)