# Controle de Medicamentos — v1.3

A v1.3 parte da base funcional da v1.2, mas será evoluída em uma aplicação independente, com banco Supabase próprio e foco mobile-first.

## Objetivos

- Preservar o fluxo que já funciona na v1.2.
- Melhorar UX/UI para celular.
- Isolar dados por paciente e conta.
- Suportar paciente e familiar/cuidador.
- Registrar cada dose prevista e cada confirmação real.
- Calcular atrasos e adesão com base nos dados reais.
- Ter alarmes e notificações confiáveis para usuários autenticados.
- Oferecer histórico, relatórios e perfil.

## Direção visual

Autenticação inspirada na referência fornecida: fundo azul abstrato, cartão branco arredondado, formulário limpo, login com Google, recuperação de senha e cadastro no mesmo estilo.

## Banco

Supabase independente da v1.2: `ivcbqeqsvtcblsbssvww`.

## Regra importante

Uma conta nova começa sem medicamentos. Medicamentos pertencem ao paciente correto e não podem aparecer para outro usuário.
