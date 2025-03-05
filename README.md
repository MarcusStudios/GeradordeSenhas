# 🔐 Gerador de Senhas Seguras em Java

## Descrição do Projeto

Este é um gerador de senhas robusto e personalizável desenvolvido em Java, projetado para criar senhas seguras com alta customização. O aplicativo permite que os usuários gerem senhas fortes com diferentes configurações de caracteres.

## 🌟 Funcionalidades

- Geração de senhas com comprimento personalizável
- Opções para incluir:
  - Letras maiúsculas
  - Letras minúsculas
  - Números
  - Caracteres especiais
- Interface de linha de comando intuitiva
- Geração de múltiplas senhas em uma única sessão
- Uso de `SecureRandom` para maior segurança criptográfica

## 🛠 Requisitos

- Java Development Kit (JDK) 8 ou superior
- Sistema operacional: Windows, macOS ou Linux

## 📦 Instalação

### Passos para Instalação:

1. Clone o repositório:
   ```bash
   gh repo clone MarcusStudios/GeradordeSenhas
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd gerador-senhas-java
   ```

3. Compile o código:
   ```bash
   javac GeradorDeSenhas.java
   ```

## 🚀 Como Usar

### Executando o Programa

```bash
java GeradorDeSenhas
```

### Fluxo de Uso

1. Digite o comprimento desejado para a senha
2. Escolha quais tipos de caracteres incluir:
   - Letras maiúsculas (s/n)
   - Letras minúsculas (s/n)
   - Números (s/n)
   - Caracteres especiais (s/n)
3. Sua senha será gerada
4. Opção de gerar nova senha ou encerrar

## 🔒 Práticas de Segurança

- Senhas geradas usam `SecureRandom`
- Comprimento mínimo recomendado: 12 caracteres
- Inclua diferentes tipos de caracteres para máxima segurança

## 📋 Exemplos

### Senha Forte
- Comprimento: 16 caracteres
- Incluir: Maiúsculas, Minúsculas, Números, Especiais
- Exemplo de Saída: `R7#kL9$mN2pQ5^xZ3`

### Senha Simples
- Comprimento: 8 caracteres
- Incluir: Apenas Maiúsculas e Números
- Exemplo de Saída: `K7N2M5P9`

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor, siga estas etapas:

1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adicionar nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## ⚖️ Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo `LICENSE.md` para detalhes.

## 📞 Contato

Seu Nome - marcuseduardo846@gmail.com



---

**Aviso de Segurança**: Nunca compartilhe suas senhas geradas. Use um gerenciador de senhas para armazenamento seguro.
