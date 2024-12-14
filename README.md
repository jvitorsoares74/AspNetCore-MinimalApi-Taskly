# Taskly

Taskly is a lightweight and efficient minimal API project built with **ASP.NET Core 8.0**, designed to streamline task management. It demonstrates the power of minimal APIs while offering a clean and straightforward implementation for task operations.

## Features

- **Task Management**: Perform CRUD (Create, Read, Update, Delete) operations on tasks.
- **Minimal API**: Utilizes the simplicity and performance of minimal APIs.
- **Lightweight Design**: Built for ease of use and scalability.
- **RESTful Endpoints**: Adheres to REST principles for seamless integration.

## Technologies Used

- **ASP.NET Core 8.0**: A modern, high-performance framework for building APIs.
- **C#**: The primary programming language for development.
- **Entity Framework Core** *(optional)*: For database interactions, if required.
- **Swagger/OpenAPI**: Provides interactive API documentation and testing.

## Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)  
- An IDE or code editor, such as [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/).

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/Taskly.git
    cd Taskly
    ```

2. **Restore Dependencies**:
    ```bash
    dotnet restore
    ```

3. **Run the Project**:
    ```bash
    dotnet run
    ```

4. **Access the API**:
    - `http://localhost:5000` for HTTP.
    - `https://localhost:5001` for HTTPS.

### Endpoints

| HTTP Method | Endpoint         | Description                 |
|-------------|------------------|-----------------------------|
| `GET`       | `/tasks`         | Retrieve all tasks          |
| `GET`       | `/tasks/{id}`    | Retrieve a task by ID       |
| `POST`      | `/tasks`         | Create a new task           |
| `PUT`       | `/tasks/{id}`    | Update an existing task     |
| `DELETE`    | `/tasks/{id}`    | Delete a task by ID         |

## Contributing

Contributions are always welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
Feel free to use, modify, and distribute this project under the terms of the license.

---
