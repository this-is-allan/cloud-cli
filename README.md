Aqui está um README.md em inglês para o seu projeto:

⸻



# 🌩️ Cloud CLI - Multi-Service Project Management

A powerful Bash script for managing projects and services via the command line. This tool provides an intuitive and efficient way to handle multiple projects and services using `tmux`, offering a seamless experience for developers.

## ✨ Features

### 📁 Project Management
- Create a new project:  
  ```sh
  cloud new <project-name>

	•	List all projects:

cloud list


	•	Each project stores its main path and associated services.

🔧 Service Management
	•	Add a service to a project:

cloud service-add <project>


	•	Remove a service:

cloud service-remove <project>:<service>


	•	Edit a service:

cloud service-edit <project>:<service>


	•	List all services of a project:

cloud services <project>



🚀 Project Execution
	•	Run all services within a project:

cloud run <project>


	•	Run specific services:

cloud run <project> <project>:<service1> <project>:<service2>


	•	Creates a tmux session with panes automatically arranged.
	•	Each pane displays the service name, directory, and execution command.

🛠️ Configuration Storage
	•	Stores project and service information in:

~/.cloud/config.json


	•	Uses the exact JSON structure as per the defined requirements.

🖥️ Terminal Interface
	•	Utilizes tmux to manage multiple services in a tiled layout.
	•	Automatically arranges panes for a better visualization.
	•	Provides a help window displaying keyboard shortcuts and active services.

📌 Installation
	1.	Clone this repository:

git clone https://github.com/your-username/cloud-cli.git


	2.	Make the script executable:

chmod +x cloud


	3.	Move it to a directory in your $PATH for global usage:

sudo mv cloud /usr/local/bin/



🛠️ Dependencies

Ensure you have the following dependencies installed:
	•	bash
	•	tmux
	•	jq (for JSON processing)

📖 Usage

After installation, you can start managing projects easily:

cloud new my-project
cloud service-add my-project
cloud run my-project

🏗️ Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

📜 License

This project is licensed under the MIT License.

---

Esse README fornece uma documentação clara e objetiva sobre o projeto. Se precisar de ajustes, posso personalizar conforme suas preferências! 🚀