# Sistema de Contrato Digital

## 📋 Descrição

Sistema completo de contrato digital com assinatura eletrônica e envio automático de emails. Desenvolvido para prestadores de serviços que precisam formalizar contratos com clientes de forma rápida e profissional.

## 🚀 Funcionalidades

### ✅ Assinatura Digital
- Canvas HTML5 para assinatura manuscrita
- Suporte a mouse e touch (dispositivos móveis)
- Validação de assinatura (detecta se foi realmente assinado)
- Formato PNG com fundo branco para melhor qualidade

### 📧 Sistema de Email Automático
- Envio automático via EmailJS
- Emails para prestador e cliente
- Inclui todas as informações do contrato
- Assinaturas digitais anexadas

### 🔐 Dados Seguros
- Armazenamento local (localStorage) 
- Validação de campos obrigatórios
- Formatação automática (CPF, telefone)
- Proteção contra alteração de dados do prestador

### 📱 Interface Responsiva
- Design profissional e limpo
- Funcionamento em desktop e mobile
- Campos auto-preenchidos (data atual)
- Experiência de usuário otimizada

## 📁 Estrutura do Projeto

```
sistema-contrato-digital/
├── contrato.html              # Sistema principal de contrato
├── contrato-visualizacao.html # Visualização do contrato assinado
└── README.md                  # Documentação
```

## ⚙️ Configuração

### EmailJS
O sistema utiliza EmailJS para envio de emails automáticos:

- **Service ID**: `service_bj6c6km`
- **Template ID**: `template_i076npw`
- **Public Key**: `E1K5MJNe_E2Dk5n7o`

### Dados do Prestador
Os dados do prestador (contratado) são fixos no sistema:

- **Nome**: Rodrigo Rocha Giuntini
- **CPF**: 491.248.858-51
- **Email**: rodrigorochagiuntini@bityx.app
- **Telefone**: (11) 99144-9842
- **Endereço**: Rua Indiana, 217 - ap 62, Brooklin - São Paulo

## 🎯 Tipos de Serviço

### Site Simples (R$ 900,00)
- Layout limpo e profissional
- Cada projeto com vídeo, imagem, título e descrição
- Responsivo para todos os dispositivos
- Sem painel de administração

### Site Completo com Painel (R$ 2.500,00)
- Inclui tudo da versão simples
- Painel administrativo com login e senha
- Permite ao cliente cadastrar e editar projetos
- Sistema escalável para futuras funcionalidades

## 🔄 Fluxo de Uso

1. **Preenchimento**: Cliente preenche seus dados
2. **Seleção**: Escolhe o tipo de serviço desejado
3. **Assinatura**: Ambas as partes assinam digitalmente
4. **Envio**: Emails automáticos são enviados
5. **Confirmação**: Redirecionamento para visualização

## 🛡️ Segurança

- Validação de email em tempo real
- Verificação de assinatura digital
- Dados do prestador protegidos contra alteração
- Armazenamento seguro no navegador

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Desktop e Mobile
- ✅ Dispositivos com touch
- ✅ Não requer instalação

## 🔧 Tecnologias Utilizadas

- HTML5 Canvas (assinatura digital)
- JavaScript ES6+
- EmailJS (envio de emails)
- CSS3 (design responsivo)
- LocalStorage (armazenamento)

## 📞 Contato

Para dúvidas ou suporte:
- **Email**: rodrigorochagiuntini@bityx.app
- **Telefone**: (11) 99144-9842

---

**Sistema desenvolvido para agilizar e profissionalizar o processo de contratação de serviços digitais.** 