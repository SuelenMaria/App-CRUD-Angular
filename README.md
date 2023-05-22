# App-Crud-Angular
Aplicativo de Cadastro (CRUD) com Criação, Leitura, Atualização e Exclusão de Produto desenvolvido com Angular 9

Autores
@SuelenMaria
Aprendizados
Durante o desenvolvimento deste projeto pude aprender mais e aplicar conhecimentos em Angular 9, tais como: Componentes, Diretivas, Pipes, Services, API Rest entre outros.

Pilha utilizada
Front-end: Angular, TypeScript

Back-end: Node, Servidor JSON

Documentação
Front-end
Este projeto foi gerado com Angular CLI versão 9.1.0.

servidor de desenvolvimento
Corra ng servepara um servidor dev. Navegue até http://localhost:4200/. O aplicativo será recarregado automaticamente se você alterar qualquer um dos arquivos de origem.

Estrutura de código
Execute ng generate component component-namepara gerar um novo componente. Você também pode usar ng generate directive|pipe|service|class|guard|interface|enum|module.

Construir
Executar ng buildpara construir o projeto. Os artefatos de construção serão armazenados no dist/diretório. Use o --prodsinalizador para uma compilação de produção.

Executando testes de unidade
Run ng testpara executar os testes unitários via Karma .

Executando testes de ponta a ponta
Run ng e2epara executar os testes de ponta a ponta via Protractor .

Mais ajuda
Para obter mais ajuda sobre o Angular CLI, use ng helpou confira o Angular CLI README .

Uso/Exemplos
#Trecho do código de product-create.component.ts

importar {Roteador} de '@angular/roteador';

@Componente({

seletor: 'app-product-create',

templateUrl: './product-create.component.html',

styleUrls: ['./product-create.component.css']

})
