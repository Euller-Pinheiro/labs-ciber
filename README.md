# labs-ciber

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-C9A84C)
![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green)

**[English below](#english)**

**Laboratórios de cibersegurança defensiva**, reproduzíveis com Docker Compose: você sobe o ambiente, vê o ataque acontecer **dentro do próprio laboratório**, e aprende a detectar e bloquear.

## Por que este projeto

Defesa se aprende vendo o ataque nos logs. Cada laboratório traz o ambiente isolado, um roteiro passo a passo, o que procurar nos registros e como responder.

> Tudo aqui roda **apenas contra contêineres do próprio laboratório**, em rede isolada. Não há exploits nem ferramentas para uso contra sistemas de terceiros.

## O que está a caminho

O projeto está sendo construído em entregas pequenas, cada uma com testes e CI. Acompanhe pelos commits e pull requests.

- [ ] Força bruta em SSH: detecção e bloqueio com fail2ban
- [ ] Análise de logs web: varredura e tentativa de SQL injection
- [ ] Regras Sigma escritas e testadas contra logs de exemplo
- [ ] Antes e depois do hardening, medido com o hardening-linux

## Tecnologias

Docker Compose · Python · Sigma · fail2ban · GitHub Actions

## Autor

**Euller Pinheiro**, Diretor Técnico da [ESX Tecnologia](https://esxtecnologia.com) — desenvolvimento de sistemas, infraestrutura e TI gerenciada em São Paulo.

---

<a name="english"></a>
## English

Defensive (blue team) cybersecurity labs with Docker Compose: watch an attack happen inside an isolated lab, then detect and block it. Lab-only, no offensive tooling. Work in progress — built in small, tested increments. Licensed under [MIT](LICENSE).
