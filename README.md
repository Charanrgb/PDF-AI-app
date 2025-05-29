Running Mistral 7B Locally using Ollama 🦙
Ollama allows you to run open-source large language models, such as Llama 2, locally. It bundles model weights, configuration, and data into a single package, defined by a Modelfile, optimizing setup and configuration details, including GPU usage.

For Mac and Linux Users: Ollama effortlessly integrates with Mac and Linux systems, offering a user-friendly installation process. Mac and Linux users can swiftly set up Ollama to access its rich features for local language model usage. Detailed instructions can be found here: Ollama GitHub Repository for Mac and Linux.

For Windows Users: For Windows users, the process involves a few additional steps, ensuring a smooth Ollama experience:

Install WSL 2: To enable WSL 2, kindly refer to the official Microsoft documentation for comprehensive installation instructions: Install WSL 2.

Install Docker: Docker for Windows is a crucial component. Installation guidance is provided in the official Docker documentation: Install Docker for Windows.

Utilize Docker Image: Windows users can access Ollama by using the Docker image provided here: Ollama Docker Image.

Now you can easily use Mistral in the command line (CMD) using the following command:

docker exec -it ollama ollama run mistral
Usage
NOTE: First install Ollama in docker and run mistral as stated above
Clone this repository:
git clone https://github.com/SonicWarrior1/pdfchat.git
Install all the depenedencies :
pip install -r requirements.txt
Open terminal and run the following command:
streamlit run app.py
