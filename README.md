# entre-trevos-fidelidade-android
# Entre Trevos Fidelidade 📱⛽

Protótipo de aplicativo Android desenvolvido como atividade de extensão da disciplina **Programação Para Dispositivos Móveis em Android** - Universidade Estácio de Sá 2026.1

Projeto realizado em parceria com o **Auto Posto Entre Trevos Ltda** - CNPJ 73.544.371/0001-08, Cristianópolis-GO.

> **Aviso**: Este é um protótipo acadêmico. Nenhum dado real de cliente ou da empresa foi utilizado. Todos os dados são simulados.

## 🎯 Objetivo
Criar um app de fidelidade onde clientes acumulam pontos a cada abastecimento e trocam por descontos, modernizando a relação do posto com a comunidade local.

**Regra de negócio**: R$1,00 = 1 ponto | 1000 pontos = R$10,00 de desconto

## 📱 Funcionalidades

| Funcionalidade | Status | Descrição |
| --- | --- | --- |
| Cadastro/Login | ✅ | Firebase Authentication com e-mail e senha |
| Saldo de Pontos | ✅ | Tela Home mostrando pontuação atualizada |
| Extrato | ✅ | Lista de transações de pontos ganhos/resgatados |
| Resgate via QR Code | ✅ | Gera QR Code para o frentista validar o desconto |
| Painel Web Admin | ✅ | Versão simplificada para gestão validar resgates |

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Kotlin
- **IDE**: Android Studio
- **Arquitetura**: MVVM + Clean Architecture
- **UI**: Material Design 3, Jetpack Compose
- **Backend**: Firebase Authentication + Cloud Firestore
- **Testes**: JUnit, Espresso para testes de UI
- **Prototipação**: Figma

## 📂 Estrutura do Projeto

app/
├── src/main/java/com/estacio/entretrevos/
│ ├── data/ # Repositórios e Firebase
│ ├── di/ # Injeção de dependência
│ ├── domain/ # Regras de negócio e models
│ └── ui/ # Telas Compose + ViewModels
└── src/test/ # Testes unitários TDD

## 🎥 Demonstração
Vídeo de 2min com o fluxo completo: [Link do YouTube não listado ou Google Drive]

## 👨‍💻 Autor
**Kayan Magalhães Gonçalves Ferreira** - Matrícula 202401517224
Curso: Análise e Desenvolvimento de Sistemas - Estácio  
Disciplina: Programação Para Dispositivos Móveis em Android  

## 📄 Licença
Projeto acadêmico para fins de avaliação. Todos os direitos da marca "Auto Posto Entre Trevos" pertencem à E & S Comercial Ltda.
