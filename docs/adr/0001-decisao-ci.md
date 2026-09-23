# ADR 001: Uso do GitHub Actions para Integração Contínua

## Contexto
O projeto precisa rodar testes automaticamente a cada Pull Request.
Existem várias ferramentas de CI no mercado (Jenkins, CicleCI, GitHub Actions).

## Decisão
Vamos usar o GitHub Actions.

## Motivo
Já hospedamos o código no GitHub, então não é preciso integrar com 
outra plataforma. é gratuito para repositórios públicos e a 
configuração fica no próprio repositóri, versionana junto com o código.

## Consquências
Ficamos dependentes do ecossistema GitHub. Se um dia migramos de
plataforma de hospedagem, o pipeline de CI precisará ser recriado.