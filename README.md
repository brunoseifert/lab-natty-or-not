# Simulação Interativa de Segurança Cibernética

## 📒 Descrição
"Simulação Interativa de Segurança Cibernética" é um projeto que utiliza IAs Generativas para criar uma experiência interativa de resposta a incidentes de segurança. Os usuários assumem o papel de analistas de segurança e tomam decisões críticas para mitigar ameaças e proteger a infraestrutura de TI. O objetivo é educar e treinar profissionais de segurança cibernética em um ambiente simulado e seguro.

## 🤖 Tecnologias Utilizadas
- **GPT-4 (OpenAI):** Utilizado para gerar cenários de incidentes, descrever ameaças e sugerir possíveis ações de mitigação.
- **Twine:** Ferramenta para criação de narrativas interativas que permite organizar os cenários e decisões.
- **Python:** Linguagem de programação utilizada para integrar a IA e o Twine.
- **Snort:** Sistema de prevenção de intrusões usado para simular detecção de ameaças.
- **Wireshark:** Ferramenta de análise de pacotes de rede para simular investigações de tráfego.

## 🧐 Processo de Criação
### 1. Planejamento
- **Definição dos Cenários:** Criação de diferentes cenários de incidentes de segurança, como ataques DDoS, phishing, e ransomware.
- **Mapeamento das Respostas:** Estruturação das respostas possíveis e suas consequências em cada cenário.

### 2. Desenvolvimento
- **Geração de Conteúdo:** Utilização do GPT-4 para criar descrições detalhadas de incidentes, incluindo logs de sistema, alertas e mensagens de ameaça.
  - Exemplo de prompt para o GPT-4: "Descreva um ataque de phishing sofisticado que visa roubar credenciais de funcionários."
- **Integração com Twine:** Uso do Twine para organizar a narrativa interativa, criando nós que representam diferentes etapas do incidente e as respostas possíveis.

### 3. Testes e Refinamento
- **Testes de Cenários:** Verificação da fluidez dos cenários e das transições entre as etapas do incidente.
- **Ajustes de Conteúdo:** Refinamento dos textos gerados para garantir clareza e realismo dos incidentes.

### 4. Publicação e Documentação
- **Publicação Online:** Disponibilização da simulação interativa em uma plataforma web.
- **Documentação:** Criação do README.md detalhando o projeto e como os usuários podem acessá-lo.

## 🚀 Resultados
- **Cenários de Incidentes:** Uma série de cenários interativos de incidentes de segurança cibernética, cobrindo várias ameaças e respostas.
- **Experiência do Usuário:** Uma experiência educativa e envolvente que ajuda a treinar profissionais de segurança cibernética em um ambiente seguro.

## 💭 Reflexão
Desenvolver uma simulação interativa de segurança cibernética com a ajuda de IAs Generativas foi um desafio interessante e recompensador. A capacidade do GPT-4 de gerar cenários realistas e contextualmente relevantes permitiu a criação de uma ferramenta de treinamento eficaz. Este projeto não só aprimorou meu portfólio, mas também demonstrou o potencial das IAs em educação e treinamento em segurança cibernética.

---

### Exemplo de Estrutura de Cenário

```markdown
# Ataque de Phishing Sofisticado

## Introdução
Você é um analista de segurança em uma grande corporação. Hoje, você recebeu um alerta de que vários funcionários relataram e-mails suspeitos tentando obter suas credenciais. O que você fará?

### Escolhas
1. **Investigar os e-mails**
2. **Ignorar o alerta**

## Investigar os e-mails
Você decide investigar os e-mails. Ao analisar o conteúdo, percebe que eles contêm links para um site de login falso que se parece exatamente com o portal da empresa.

### Escolhas
1. **Alertar todos os funcionários sobre o phishing**
2. **Desativar temporariamente o portal de login verdadeiro**

## Alertar todos os funcionários
Você envia um e-mail a todos os funcionários, alertando-os sobre o ataque de phishing e instruindo-os a não clicarem nos links suspeitos.

### Consequências
- **Positivas:** A maioria dos funcionários evita o phishing, e a tentativa de ataque é amplamente evitada.
- **Negativas:** Alguns funcionários já clicaram no link antes de receber o alerta, comprometendo suas credenciais.

(E assim por diante, expandindo cada escolha com novas ramificações e desenvolvimentos de incidentes)
