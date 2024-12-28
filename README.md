# ODE Solver Using Physics-Informed Neural Networks with Microservices Architecture

## Introduction

This project presents a hybrid approach for solving ordinary differential equations (ODEs) by integrating Physics-Informed Neural Networks (PINNs) with a microservices architecture. PINNs leverage the governing physical laws in the loss function of the neural network to solve complex ODEs more efficiently. The microservices architecture ensures modularity, scalability, and ease of integration, allowing the solution to be applied to both boundary value problems (BVPs) and initial value problems (IVPs) in a wide range of scientific and engineering applications.

### Key Features:
- Solves first and second-order ODEs.
- User-defined initial and boundary conditions.
- Real-time solution visualization.
- Export solutions in PDF or CSV formats.
- Email results directly from the application.

## Architecture

The system is designed using a **microservices architecture**, which ensures flexibility and scalability. The key components are:

### 1. Frontend:
- Built using **Angular**, providing an interactive user interface that allows users to input their ODEs and view results.

### 2. Backend:
- Developed using **Flask** and **Java Spring Boot**, responsible for processing user inputs, managing computation tasks, and handling API requests.

### 3. AI Engine:
- A **PyTorch-based** module implements the PINN framework to solve the ODEs efficiently.

### 4. DevOps:
- **Jenkins** and **SonarQube** are integrated for continuous integration, testing, and code quality assurance, ensuring that the code remains stable and secure.

### System Architecture:

![System Architecture](![archi](https://github.com/user-attachments/assets/c069ec12-6b84-491d-a874-9cef0fb65f0b)
)

## Technologies and Tools

- **Frontend**: Angular
- **Backend**: Flask, Java Spring Boot
- **AI Engine**: PyTorch (for implementing PINNs)
- **DevOps**: Jenkins, SonarQube
- **Programming Languages**: Python 3.x, Java 17+
- **Other Tools**: Git, VPS server, NumPy
- **License**: MIT License

## Demo


https://github.com/user-attachments/assets/8c3f45c9-9b8a-4211-a47b-d0db732c7a2a



To run the demo locally, follow these steps:

### Prerequisites:
- Python 3.x
- Java 17+
- Node.js (for Angular frontend)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/asmachkirida/pinn-de-solver.git
   cd pinn-de-solver

## Contributors
- **Asma Chkirida** 
- **Yassine Chalati** 
- **Yasser Afzaz** 
- **Acharf Bouabdelli** 
- **Ismael Benzbair** 

## License
This project is licensed under the **MIT License** - see the LICENSE file for details.

## Contact
For questions or support, contact:
- **Email**: [asmachkirida02@gmail.com](mailto:asmachkirida02@gmail.com)


