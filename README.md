# Sistema de Reservas de Cinema

## Sobre o projeto
O sistema serve para reservar assentos no cinema.

## Regras de negócio
- Um assento não pode ser reservado duas vezes na mesma sessão.
- Uma reserva cancelada não pode ser confirmada.
- O pagamento só é processado se a reserva estiver pendente.
- O pagamento recusado deixa a reserva pendente por até 10 minutos.
  Timeout verificado sob demanda, não em background (escopo simplificado pra v1).
- Reserva pendente por mais de 10 minutos é cancelada automaticamente.

## Decisões de design

## Como rodar o projeto
