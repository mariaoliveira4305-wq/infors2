# infors2
========== SISTEMA DE BEM-ESTAR ESCOLAR ==========

✅ Sistema inicializado com sucesso
   Alunos: 2
   Professores: 1
   Psicólogos: 1

--- TESTE 1: LOGIN ---
Login bem-sucedido
Usuário: João Silva (student)

--- TESTE 2: REGISTRAR ANSIEDADE ---
Ansiedade registrada
Nível: 6 | Em risco: false

Ansiedade registrada
Nível: 8 | Em risco: true

--- TESTE 3: ALUNOS EM RISCO ---
Total em risco: 1
  • João Silva: Nível 8/10

--- TESTE 4: AGENDAR SESSÃO ---
Agendamento criado
Data: 2024-06-15T00:00:00.000Z
Hora: 14:00

--- TESTE 5: POLIMORFISMO - PERMISSÕES ---

👨‍🎓 Aluno:
  ✓ view_own_grades
  ✓ view_own_anxiety_data
  ✓ submit_assignments

👨‍🏫 Professor:
  ✓ view_student_grades
  ✓ create_assignments
  ✓ view_anxiety_levels
  ✓ message_students

👨‍⚕️ Psicólogo:
  ✓ view_all_anxiety_data
  ✓ manage_appointments
  ✓ record_interventions
  ✓ generate_reports

👨‍💼 Admin:
  ✓ manage_users
  ✓ delete_users
  ✓ view_all_data
  ✓ generate_reports
  ✓ system_config

--- TESTE 6: RELATÓRIO FINAL ---
Total de usuários: 5
Alunos: 2
Professores: 1
Psicólogos: 1
Alunos em risco: 1

--- TESTE 7: TRATAMENTO DE ERROS ---
✗ Usuário não encontrado
✗ Nível deve estar entre 0 e 10

========== FIM DO TESTE ==========
