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
| Login | ✅ | Tela de login com dados simulados |
| Saldo de Pontos | ✅ | Tela Home mostrando 1.250 pontos mockados |
| Extrato | ✅ | Lista de 3 transações simuladas |
| Resgate via QR Code | ✅ | Gera QR Code local com ZXing |
| Painel Web Admin | ⏳ | Planejado para v2 |

## 🛠️ Tecnologias Utilizadas
- **Linguagem**: Kotlin
- **IDE**: Android Studio Hedgehog
- **Arquitetura**: MVVM
- **UI**: Material Design 3, Jetpack Compose
- **Bibliotecas**: Navigation Compose, ZXing para QR Code
【5699748840685172590†L25-L33】【5699748840685172590†L45-L47】

## 📂 Estrutura do Projeto

app/
├── src/main/java/com/estacio/entretrevos/
│ ├── data/ # Repositórios e Firebase
│ ├── di/ # Injeção de dependência
│ ├── domain/ # Regras de negócio e models
│ └── ui/ # Telas Compose + ViewModels
└── src/test/ # Testes unitários TDD

## ▶️ Como Executar
1. Clone o repositório
2. Abra no Android Studio Hedgehog+
3. Aguarde o Gradle Sync
4. Rode em um emulador API 24+ ou dispositivo físico

**APK para teste**: [Baixar APK](/apk/app-debug.apk)

## 🎥 Demonstração
Vídeo de 1min com o fluxo completo: [[Link do YouTube](https://youtu.be/zJWYNEnbp8c)]

## 👨‍💻 Autor
**Kayan Magalhães Gonçalves Ferreira** - Matrícula 202401517224
Curso: Análise e Desenvolvimento de Sistemas - Estácio  
Disciplina: Programação Para Dispositivos Móveis em Android  

## 📄 Licença
Projeto acadêmico para fins de avaliação. Todos os direitos da marca "Auto Posto Entre Trevos" pertencem à E & S Comercial Ltda.
