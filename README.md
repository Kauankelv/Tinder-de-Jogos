# Tinder de Jogos

## Descrição
Este é um projeto de um aplicativo estilo Tinder para jogos, onde jogadores podem se conectar com base em preferências e interesses em comum. O projeto utiliza **ASP.NET Core API + Firebase** no backend e **Blazor + .NET MAUI Hybrid** no frontend.

## 🛠️ Tecnologias Utilizadas
- **Backend:** ASP.NET Core API, Firebase Authentication
- **Frontend:** Blazor + .NET MAUI Hybrid
- **Banco de Dados:** Firestore (Firebase)

## 📂 Estrutura do Projeto
```
TinderJogo/
│── Backend/             # API ASP.NET Core + Firebase
│   ├── Controllers/     # Controladores da API
│   ├── Models/          # Modelos de dados
│   ├── Services/        # Lógica de negócios (Firebase, matchmaking, etc.)
│   ├── Program.cs       # Entrada do programa (backend)
│   ├── appsettings.json # Configurações do projeto
│   └── firebase-config.json # Credenciais do Firebase
│
│── Frontend/            # Blazor + .NET MAUI Hybrid
│   ├── wwwroot/         # Arquivos estáticos
│   ├── Pages/           # Páginas do Blazor
│   ├── Components/      # Componentes reutilizáveis
│   ├── Services/        # Comunicação com a API
│   ├── App.razor        # Componente principal
│   ├── Main.razor       # Entrada do app MAUI
│   └── Program.cs       # Configuração do Blazor MAUI
│
│── README.md            # Documentação do projeto
│── .gitignore           # Arquivos a serem ignorados no Git
```

## 🚀 Como Rodar o Projeto

### Backend
1. **Instalar dependências**
   ```sh
   dotnet restore
   ```
2. **Rodar a API**
   ```sh
   cd Backend
   dotnet run
   ```

### Frontend
1. **Instalar dependências**
   ```sh
   dotnet restore
   ```
2. **Rodar o aplicativo**
   ```sh
   cd Frontend
   dotnet build
   dotnet run
   ```


## 📌 Contribuição
Sinta-se à vontade para contribuir! Faça um fork do repositório e envie PRs com melhorias.



