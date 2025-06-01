# Projeto Educacional de Ransomware - Fins Didáticos

## Objetivo
Demonstrar técnicas de criptografia para fins de estudo em segurança cibernética.

## ⚠️ Aviso Importante
**Este projeto não deve ser usado para atividades maliciosas.** Ransomware é um crime cibernético grave, e este código foi desenvolvido exclusivamente para fins acadêmicos.

## 🔒 Funcionalidades Implementadas

### 1. Criptografia AES-256 (`encrypter.py`)
![Interface do Encrypter](imagens/encrypter.png)  
*Figura 1: Tela de execução do script de criptografia*

- Realiza criptografia de arquivos usando AES-256
- Modifica extensões (ex: `.txt` → `.txt.encrypted`)
- Registra operações em `ransomware.log` (opcional)

### 2. Descriptografia controlada (`decrypter.py`)
![Interface do Decrypter](imagens/decrypter.png)  
*Figura 2: Processo de descriptografia dos arquivos*

- Reverte a criptografia usando a mesma chave AES
- Restaura arquivos ao formato original
- Valida integridade dos dados

### 3. Backup Automático (Opcional)
- Cria cópias de segurança antes de modificações
- Previne perda acidental de dados

## 📸 Demonstração Completa
![Fluxo completo do desafio](imagens/image.png)  
*Figura 3: Sequência completa no terminal*

## 📌 Como Usar para Aprendizado
1. **Execute em ambiente controlado** (VM ou container)
2. **Analise o código** para entender:
   - Implementação do AES
   - Fluxo de criptografia
3. **Teste com arquivos não críticos** (ex: `teste.txt`)
4. **Explore contramedidas**:
   - Detecção de alterações suspeitas
   - Mecanismos de recuperação sem resgate

## 🎯 Objetivos de Aprendizado
- Compreender **criptografia simétrica** (AES)
- Praticar **manipulação segura de arquivos** em Python
- Discutir **implicações éticas** no desenvolvimento
- Preparar para **blue team** (defesa cibernética)

## 📁 Estrutura do Projeto