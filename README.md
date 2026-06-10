# infors2
// 1. Criar sistema
const system = new SchoolSystem();
system.initialize();

// 2. Login
const login = system.login('joao@email.com', 'senha123');
console.log('Bem-vindo,', login.user.name);

// 3. Registrar ansiedade
const anxiety = system.registerAnxiety(1, 8, ['tremores']);
console.log('Aluno em risco:', anxiety.data.isAtRisk);

// 4. Agendar sessão
const appt = system.scheduleAppointment(4, 1, new Date('2024-06-15'), '14:00');
console.log('Agendado para:', appt.data.date);

// 5. Ver alunos em risco
const atRisk = system.getAtRiskStudents();
console.log('Alunos em risco:', atRisk.length);

// 6. Gerar relatório
const report = system.getReport();
console.log('Total de usuários:', report.totalUsers);
