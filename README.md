# desafio-ataque-brute-force-medusa
Desafio do curso de Cibersegurança Santander 2025 - Simulando um Ataque de Brute Force de Senhas com Medusa


Este desafio prático foi essencial para simular cenários reais onde a segurança é comprometida devido à **negligência de configurações básicas e falhas humanas**. As capturas de tela e os arquivos anexos neste repositório demonstram a execução dos seguintes módulos:

### 1. Módulos Práticos Concluídos

O projeto focou na exploração de vulnerabilidades em ambientes de teste (Metasploitable 2 e DVWA), abordando as seguintes técnicas:

* **Acesso a Máquinas Vulneráveis:** Alcançando a máquina `Metasploitable 2`, que serve como alvo prático para testes de intrusão.
* **Ataques de Força Bruta e Dicionário:**
    * Criação e uso de **Wordlists** e listas de usuários (Customização de dicionários).
    * Simulação de ataques de Força Bruta em **formulários de login em sistemas web** (conforme demonstrado na exploração do DVWA - ).
    * Utilização da ferramenta **Medusa** para simular combinações entre usuários e senhas (Password Spraying) em serviços de rede, buscando credenciais fracas ou padrão (conforme a imagem de terminal - ).
* **Ataque em Cadeia e Enumeration:**
    * Execução de um **Ataque em Cadeia** envolvendo a enumeração do protocolo **SMB (Server Message Block)**.
    * Teste de acesso utilizando o `smbclient` para identificar compartilhamentos e obter informações (conforme a imagem de terminal - ), simulando um **cenário corporativo mal configurado**.

### 2. Reflexões e Opiniões

O ponto crucial deste desafio é a **falha de segurança que ocorre quando o básico é negligenciado**. O sucesso nos ataques simulados reforça as seguintes conclusões estratégicas:

#### 🚨 Principais Falhas de Segurança Observadas:
* **Servidores Expostos e Mal Configurados:** A facilidade de acesso a serviços de rede (como FTP e SMB) ou a aplicações web vulneráveis demonstra a negligência em configurações padrão de segurança.
* **Senhas Fracas e Reutilizadas:** A quebra de credenciais via ataques de dicionário e *password spraying* é uma evidência direta do risco associado a senhas previsíveis, fracas ou reutilizadas.
* **Padrões Previsíveis:** A falta de auditoria de segurança básica expõe padrões que podem ser explorados rapidamente.

#### ✅ Medidas de Mitigação Propostas:
Para combater as vulnerabilidades exploradas, é essencial investir em uma postura de defesa proativa, incluindo:
* **Políticas de Senhas Fortes e Autenticação:** Implementação obrigatória de políticas de senhas complexas e, crucialmente, a adoção de **Autenticação Multifatores (MFA)** em todos os serviços críticos.
* **Monitoramento Inteligente:** Investir em sistemas de **detecção de comportamento anômalo** e bloqueio automático por IP após tentativas falhas.
* **Auditorias de Segurança Regulares:** A segurança deve ser um processo contínuo. É vital realizar **auditorias regulares** com ferramentas de simulação de ataque para que as equipes de segurança possam explorar possíveis vetores de ataque **antes** que sejam explorados por invasores.

Em última análise, o desafio é um reflexo sobre as **falhas humanas e a negligência em nível organizacional**, sublinhando que a segurança robusta começa com o cuidado rigoroso dos detalhes básicos.

<img width="1710" height="969" alt="Image" src="https://github.com/user-attachments/assets/b7dc92d2-edf0-4004-adb7-3b5c813d40b2" />
<img width="1913" height="905" alt="Image" src="https://github.com/user-attachments/assets/16a9c009-6673-43e1-82a5-be15ae64baf0" />
<img width="1316" height="621" alt="Image" src="https://github.com/user-attachments/assets/98e9e070-8629-40bc-9639-b9eee8859969" />
