# 🍔 Exemplo de Pacotes Java - Sistema de Lanchonete

Este projeto demonstra o uso de **pacotes (packages)** em Java através de um sistema simplificado de lanchonete. O projeto ilustra como organizar classes em diferentes pacotes para melhor estruturação e organização do código.

## 📁 Estrutura do Projeto

```md
src/
└── lanchonete/
├── Estabelecimento.java # Classe principal (main)
├── area/
│ └── cliente/
│ └── Cliente.java # Funcionalidades do cliente
└── atendimento/
├── Atendente.java # Funcionalidades do atendente
└── cozinha/
├── Cozinheiro.java # Funcionalidades do cozinheiro
└── Almoxarife.java # Controle de estoque
```

## 🎯 Objetivos do Projeto

- Demonstrar a organização de código usando pacotes Java
- Mostrar a separação de responsabilidades entre diferentes áreas do sistema
- Ilustrar o uso de modificadores de acesso (public, private, package-private)
- Exemplificar a estruturação de um projeto Java real

## 🏗️ Arquitetura do Sistema

### **Estabelecimento** (Classe Principal)

- Coordena todas as operações da lanchonete
- Cria instâncias das diferentes classes
- Simula o fluxo de trabalho da lanchonete

### **Área do Cliente**

- **Cliente**: Responsável por escolher lanches, fazer pedidos e pagar contas
- Funcionalidades incluem consulta de saldo no aplicativo

### **Área de Atendimento**

- **Atendente**: Gerencia o serviço de mesa, recebimento de pagamentos e troca de gás
- **Cozinheiro**: Prepara lanches, sucos e combos, além de gerenciar ingredientes
- **Almoxarife**: Controla entrada/saída de itens e troca de gás

## 📋 Funcionalidades Implementadas

### Cliente

- ✅ Escolher lanche
- ✅ Fazer pedido
- ✅ Pagar conta
- ✅ Consultar saldo no aplicativo

### Atendente

- ✅ Servir mesa
- ✅ Receber pagamento
- ✅ Trocar gás
- ✅ Pegar pedidos no balcão

### Cozinheiro

- ✅ Preparar lanches (hambúrgueres)
- ✅ Preparar sucos/vitaminas
- ✅ Preparar combos
- ✅ Selecionar e lavar ingredientes
- ✅ Fritar ingredientes
- ✅ Solicitar troca de gás
- ✅ Solicitar ingredientes ao almoxarife

### Almoxarife

- ✅ Controlar entrada de itens
- ✅ Controlar saída de itens
- ✅ Entregar ingredientes
- ✅ Trocar gás

## 🔧 Tecnologias Utilizadas

- **Java** - Linguagem de programação principal
- **Pacotes Java** - Organização e estruturação do código
- **Modificadores de Acesso** - Controle de visibilidade das classes e métodos

## 📚 Conceitos Demonstrados

### Pacotes Java

- Organização hierárquica de classes
- Separação por responsabilidade
- Importação entre pacotes

### Modificadores de Acesso

- `public` - Acesso público
- `private` - Acesso restrito à própria classe
- `package-private` (padrão) - Acesso dentro do mesmo pacote

### Encapsulamento

- Métodos privados para operações internas
- Métodos públicos para interface externa
- Controle de acesso entre classes

## 🎓 Aprendizados

Este projeto demonstra:

1. **Organização de Código**: Como estruturar um projeto Java usando pacotes
2. **Separação de Responsabilidades**: Cada classe tem uma função específica
3. **Modificadores de Acesso**: Controle de visibilidade e acesso
4. **Relacionamentos entre Classes**: Como classes se comunicam entre si
5. **Estrutura de Projeto**: Organização de diretórios e arquivos

## 🤝 Contribuição

Este é um projeto de exemplo para fins educacionais. Sinta-se à vontade para:

- Fazer fork do projeto
- Sugerir melhorias
- Reportar problemas
- Contribuir com novas funcionalidades

## 📄 Licença

Este projeto é de código aberto e está disponível para fins educacionais.

---

**Desenvolvido para demonstrar conceitos de pacotes em Java** 🎯
