# Editor de Texto Básico

![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk)
![JavaFX](https://img.shields.io/badge/JavaFX-21-blue?style=flat-square)
![License](https://img.shields.io/badge/Licença-MIT-green?style=flat-square)

## 📌 Sobre o Projeto

Aplicação desktop desenvolvida em Java com JavaFX que funciona como um editor de texto simples. Permite escrever livremente em uma área de texto e salvar o conteúdo em um arquivo no sistema operacional. Projeto criado para consolidar os fundamentos de interfaces gráficas com JavaFX.

## 🚀 Tecnologias Utilizadas

- Java 21
- JavaFX 21
- Eclipse IDE

## 🖥️ Funcionalidades

- Área de texto editável (800×600)
- Botão "Salvar" na barra de ferramentas
- Seleção de destino e nome do arquivo via `FileChooser`
- Gravação do conteúdo digitado em arquivo de texto

## ▶️ Como Executar

### Pré-requisitos

- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)
- [JavaFX SDK 21](https://gluonhq.com/products/javafx/)
- Eclipse IDE (com suporte a JavaFX configurado)

### Configuração no Eclipse

1. Baixe e extraia o JavaFX SDK 21.
2. No Eclipse, vá em **Window → Preferences → Java → Build Path → User Libraries**.
3. Crie uma User Library chamada `JavaFX` e adicione todos os `.jar` da pasta `lib` do SDK.
4. Clone o repositório:
   ```bash
   git clone https://github.com/MarceloJustin/editor-de-texto-basico-javafx.git
   ```
5. Importe o projeto no Eclipse: **File → Import → Existing Projects into Workspace**.
6. Certifique-se de que a User Library `JavaFX` está no Build Path do projeto.
7. Adicione os seguintes VM arguments em **Run Configurations → Arguments → VM args**:
   ```
   --module-path /caminho/para/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
   ```
8. Execute a classe `Main.java`.

## 👨‍💻 Autor

**Marcelo Justin**

[![GitHub](https://img.shields.io/badge/GitHub-MarceloJustin-181717?style=flat-square&logo=github)](https://github.com/MarceloJustin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marcelojustin-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/marcelojustin)

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
