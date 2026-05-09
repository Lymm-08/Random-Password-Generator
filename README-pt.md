```markdown
# Gerador de Senhas Aleatórias

Projeto em **Python** para geração de senhas personalizadas.  
Disponível em duas versões: **interface gráfica (Tkinter)** e **terminal (CLI)**.

---

## Funcionalidades
- Definir o comprimento da senha  
- Incluir letras, números e símbolos  
- Salvar senhas em arquivo `.txt`  
- Histórico de senhas geradas  
- Copiar senha diretamente para a área de transferência  

---

## Como Executar

### 1. Criar e ativar ambiente virtual
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1   # no PowerShell
```

### 2. Instalar dependências
```bash
pip install pyperclip
```

### 3. Executar o programa
```bash
python main.py
```

---

## Demonstração
![Demonstração do programa](GeradorSenhasAleatorias/imagens/demo.gif)

---

## Exemplo de Uso (Interface Gráfica)
1. Informe o comprimento desejado da senha  
2. Selecione se deseja incluir letras, números e símbolos  
3. Clique em **Gerar Senha**  
4. Utilize os botões para salvar, copiar ou visualizar o histórico  

---

## Exemplo de Uso (Terminal/CLI)
```
=== Gerador de Senhas Aleatórias ===
Digite o comprimento da senha: 12
Incluir letras? (s/n): s
Incluir números? (s/n): s
Incluir símbolos? (s/n): n

Sua senha gerada é:
a9BfK2LmQwXz
```

---

## Tecnologias Utilizadas
- **Python 3**  
- **Tkinter** (interface gráfica)  
- **Pyperclip** (cópia para área de transferência)  
- **GitHub** para versionamento e controle de código  

---

## Diferenciais Técnicos
- Disponibilidade em **modo gráfico** e **modo terminal**  
- Persistência de senhas em arquivo `.txt`  
- Histórico de senhas para consulta posterior  
- Estrutura modular e organizada para fácil manutenção  

---

## Próximos Passos
- Melhorar a interface gráfica (cores, estilos, responsividade)  
- Adicionar opção para escolher o diretório de salvamento  
- Criar versão em **PyQt** para interface mais avançada  
- Implementar exportação de senhas em diferentes formatos (JSON, CSV)  

---
