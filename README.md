# Add readme content here how to execute the project locally
To run this project locally, follow these steps:
1. **Clone the Repository**:
   Open your terminal and run the following command to clone the repository:
   ```
   git clone <repository_url>
   ```
   Replace `<repository_url>` with the actual URL of the repository.
2. **Navigate to the Project Directory**:
   Change your current directory to the project folder:
   ```
    cd <project_directory>
    ```
    Replace `<project_directory>` with the name of the cloned repository folder.
3. **Install Hugo**:
    Make sure you have Hugo installed on your machine. You can download it from [Hugo's official website](https://gohugo.io/getting-started/installing/).

    Run Powershell (Docker - No local install needed):
    ```
    docker run --rm -it -p 1313:1313 -v "${PWD}:/src" -w /src klakegg/hugo:ext server --bind=0.0.0.0 -D
    ```
4. **Run the Hugo Server**:
   Start the Hugo development server by running:
   ```
    hugo server
    ```
5. **Access the Local Site**:
   Open your web browser and navigate to `http://localhost:1313` to view the site locally.
6. **Make Changes**:
   You can now make changes to the project files. The Hugo server will automatically reload the site to reflect your changes.

