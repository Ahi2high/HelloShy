HelloShyanne
This is a simple WPF (Windows Presentation Foundation) application that greets the user with a message.

Getting Started
Follow these instructions to get the project up and running on your local machine.

Prerequisites
Visual Studio (2017 or later)
.NET Framework
Installation
Clone the Repository: Clone this repository to your local machine using Git.

bash
Copy code
git clone https://github.com/Ahi2high/HelloShy.git
Open Solution in Visual Studio: Navigate to the cloned repository folder and open the solution file (HelloShyanne.sln) in Visual Studio.

Build Solution: Build the solution in Visual Studio to ensure all dependencies are resolved and the project compiles successfully.

Usage
Open MainWindow.xaml: Open the MainWindow.xaml file located in the HelloShyanne project folder.

Modify UI Elements (Optional): You can modify the UI elements such as text blocks, text boxes, and buttons to customize the appearance of the application.

Modify Code (Optional): If you want to modify the functionality of the application, open the MainWindow.xaml.cs file and make changes to the code as needed. For example, you can customize the greeting message or add additional features.

csharp
Copy code
private void OkClick(object sender, RoutedEventArgs e)
{
    string shyanneText = ShyanneTextBox.Text;
    MessageBox.Show($"Hello {shyanneText}");
}
Run the Application: Press F5 or click on the "Start" button in Visual Studio to run the application. The application window will appear, allowing you to interact with it.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
