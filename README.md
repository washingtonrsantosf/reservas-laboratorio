**RESERVAS DO LABORATÓRIO DE INFORMÁTICA**

Site para professores reservarem horários no laboratório de informática da escola. Cada professor cria sua conta, vê a agenda do dia e reserva um horário livre. O sistema não deixa duas reservas ocuparem o mesmo horário.

Site publicado: https://agendainfo.netlify.app

O projeto nasceu de uma planilha de controle de reservas (data, dia, início, fim, professor e disponibilidade) e foi transformado em um sistema com banco de dados, que funciona no computador e no celular.

**O QUE O SITE FAZ:**

Login e criação de conta com e-mail e senha

Agenda da semana (segunda a sexta), com navegação entre semanas

Linha do tempo do dia, com as reservas de cada professor

Reserva de horário tocando em um espaço livre da agenda ou preenchendo início, fim e turma

Bloqueio de conflito: não é possível reservar um horário já ocupado

Cancelamento: o professor cancela as próprias reservas; o administrador cancela qualquer uma

Destaque do dia de hoje, dias passados apagados e linha vermelha do horário atual

Modo escuro automático, conforme a configuração do aparelho

**TECNOLOGIAS**

HTML, CSS e JavaScript puro (sem frameworks e sem etapa de build)

Supabase: banco de dados e login com e-mail e senha

GitHub: guarda o código

Netlify: publica o site
